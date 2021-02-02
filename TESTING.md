#<p align="center">Testing for [Paco's Wing Bar](https://russoakham.github.io/ci-milestone-project-1/)</p>

## Validation

### W3 HTML
I validated the HTML with [W3 Validation Service](https://validator.w3.org/). The results can be seen below;
 - [index](design-resources/testing/HTML/before/home.PNG)
 - [about us](design-resources/testing/HTML/before/about-us.PNG)
 - [menu](design-resources/testing/HTML/before/menu.PNG)
 - [reservation](design-resources/testing/HTML/before/reservation.PNG)

 **Errors**
 The reservation form section showed an error at first, this is because the option is marked as "required", as the first option must either have an empty 'value' attribute or have no text content. The fix to this is to add a 'disabled value' showing placeholder text.

 **Warnings**
 All pages showed warnings regarding HTML semantics and use of H1's and H2-6's in sections, however upon review I am happy that all headings are relevant and each page has a relevant unique H1. So I decided to enact any changes. 

### W3 CSS 
I also validated the CSS with the [w3 Validation Service](https://jigsaw.w3.org/css-validator/) and it found no errors.

Screenshots for Final Validations passes can be seen below;
 - HTML:
    - [index](design-resources/testing/HTML/after/index.PNG)
    - [about us](design-resources/testing/HTML/after/about.PNG)
    - [menu](design-resources/testing/HTML/AFTER/menu.PNG)
    - [reservation](design-resources/testing/HTML/after/reservation.PNG)
 - CSS: [style.css](design-resources/testing/CSS/css-validation.PNG)

### Google Lighthouse Audit
I used Google's lighthouse audit to test the website conforms positively with Googles performance metrics, with the aim for achieving scores of 90 in all areas on desktop.

After initial testing, the performance metric was below 90, while Accessibility, Best Practices and SEO were low 90's. To improve this i carried out the below actions;

**Performance** - Converted all images from .jpg to .webP, which offers improved compression and therefore quicker loading times. I used the website [caniuse](https://caniuse.com/webp), to ensure webp is compliant with all major web browsers, which it is.

**Accessibility** - Added rel="noopener" and rel="noreferrer" to social media links in footer, to avoid passing of any site information to external sites.

**Best Practices** - Added a 'title' to google map iframe, for improved semantics.

**SEO** - Added meta descriptions for all pages providing an overview of page content and intent.

These changes improved all metrics to the below passing scores;

![Google Lighthouse Audit Score](design-resources/testing/google-lighthouse-audit.PNG)

## Responsive Browser & Device Testing
To test the responsiveness of the site I used [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools), [Responsive Design Checker](https://www.responsivedesignchecker.com/) and [BrowserStack](https://www.browserstack.com/).

### Responsiveness
![Desktop Responsiveness](design-resources/testing/responsive-desktop.PNG)

![Tablet Responsiveness](design-resources/testing/responsive-tablet.PNG)

![Mobile Responsiveness](design-resources/testing/responsive-mobile.PNG)

I founnd only a few small issue, all on very small mobile devices, where the extra thin viewport caused issues visual issues. 

The first issue was content overflowing the yellow content boxes, such as the opening hours table. To rectify this I included an additional media query to reduce padding of yellow content boxes to 20px left and right, and remove column padding in the opening hours table.

The second issue was the call-to-action container on the homepage banner covered the near entirety of the banner image. To improve this i added a small screen size media query reducing margin and padding to the following css classes; 'hero-callout p','hero-header' and 'heading-divider'. These changes allowed more of the background image to be visible.

### Browser Compatability
![Browser Compatability](design-resources/testing/browser-compatability.PNG)

The site works well on all browsers except for Internet Explorer, which fails to load the images as the webP image format is not supported.
According to [caniuse](https://caniuse.com/usage-table) the current usage of Internet Explorer is just 1.1% or total browser users, therefore I am comfortable to not support IE in the site design.

Note: Microsoft released Internet Explorer in 2013 and actively developed the browser until 2015, when Microsoft Edge was released as it's replacement. Since 2015, the only updates for IE have been security patches and bug fixes.

## Testing User Stories




## Issues I had to overcome
Overall production of the site was smooth, where I only encountered a few small issues;

- **Homepage Banner**: On the home page, the yellow banner slightly blended into the background due to the background's natural yellow hew. To remove this blending, I added a 'box-shadow' effect via CSS to provide a natural effect border. I liked the effect so much, I've applied this to other elements throughout the site.

- **Yellow Content Box & Team-Card Sizing**: Due to the content of the various boxes being different lengths, the yellow boxes and team-cards would size differently on various viewport sizes. This gave a messy look, as evidenced below;

![Yellow-Content-Box Auto Sized](design-resources/testing/yellow-box-incorrect-sizing.PNG)

To ensure a clean look, I wanted to ensure all elements were uniform in size. To enable this I added a 'min-height' css rule to the '.yellow-content-box' class, plus additional media-queries using bootstrap breakpoints, to ensure uniform height across devices.

![Yellow-Content-Box Auto Sized](design-resources/testing/yellow-box-correct-sizing.PNG)

- **Google Map iframe**: Similar to the yellow-content-boxes, I had to add media-queries to the iframe embedding the google map, to ensure this resized in line with it's partnered yellow content box. As the google map element is sized by the 'padding-bottom' css rule, I had to use this rather than 'min-height'.

- **logos and menu pdf**: As this is a new business, I had to create an original logo and menu. To accomplish this I used [Canva](https://www.canva.com/), which provided templates I was able to adapt. I used the colours as noted under the 'UX' section to ensure they aligned to branding.

- **Favicons**: I used [Real Favicon Generator](https://realfavicongenerator.net/) to create favicon images, for use across windows, iOS and android based devices.
The generator does advise the files be placed directly into the website root, however for file cleanliness I decided to place these in a [sub-directory](assets/images/favicons). After testing, it appears to not have caused an issue for favicons to be working correctly.

- **Team Card Images**: The images on the team card would stretch vertically when viewed on a thin screened device, such as my iPhone XR. This is because the images were under the "card" classes 'display: flex' and 'flex-direction: column" rules. To rectify this, I wrapped the images in their own div and use this as my styling class for the images. 

## Issues still to overcome
- **Online Reservation Form**: Currently the form allows booking for the restaurant's static open hours of 12pm-10pm Monday-Sunday. However so as to allow the restaurant to open different hours on different days and also to close for certain days (e.g. christmas), the form needs to be updated so the available booking slows can be dynamically updated.
To achieve this I would need to implement javascript to the form, which is currently outside my expertise.
Alternatively, I'd advise the client to partner with a third party provider who provides online booking solutions such as [Opentable](https://www.opentable.co.uk/). This could then be directly embedded to the booking page, allow owners to easily update booking availability without the need of developer help and would offboard the need for future development to the third party.
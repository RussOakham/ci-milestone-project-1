# Milestone 1 - Paco’s Wing Bar - by Russell Oakham

## Project overview

The project is a small website for a restaurant based in Bristol. The main purpose would be to get people interested in booking a reservation at the restaurant. The website promotes that the restaurant is a small independant business, whose menu is inspired by international street food. 

![Responsive demo](developer-resources/testing/responsive-demo.PNG "Responsive demo")

## UX

Overview of UX decisions, structure etc. Examples of websites I have viewed as part of research & UX decisions from it.

### User Stories

## Ideal Client
The websites ideal client would be:
 - English speaking.
 - Have disposable income for eating out.
 - Individual with a keen interest in modern street food.

Visitors to this website are searching for:
 - Restaurants in Bristol, specialising in chicken wings and burgers.
 - Restaurants in Bristol, run independently.
 - Restaurants in Bristol, with an upbeat atmosphere.

 ## Strategy
The main goals of the website are:

 1. To entice potential customers to book a table reservation with the restaurant. Via either submitting of a booking request via the online form or contacting the restaurant via phone or e-mail.
 2. To raise brand awareness of the restaurant, to entice potential customers to visit teh restaurant without a reservation i.e. 'promote walk-ins'.
 3. To allow returning visitors to quickly navigate to Contact Details and Booking pages.
 4. To allow potential and returning customers easy navigation to the menu page, allowing the quick perusal of products offered.

### Scope
This section determines what the users should be able to do on the website.

1. Enquire for a table reservation using online booking system.
2. Contact the restaurant to enquire around bookings or for further information.
3. Find out where the retaurant is located.
4. Find out more information about the restaurant, it's ethos and it's staff
5. View current menu options the restaurant currently provides.

### Structure
At this point I started thinking about what information, pages, features, and calls to action were to necessary and how they would be grouped.

I wanted to keep the structure simple, restricting design to 4-5 key content pages so potential customers would not feel overwhelmed or 'spammed' by irrelevant information. I identified key content pages to be;

- Home Page: Containing brief overview of restaurants ethos, call-to-action (book online), location and contact details.
- About Us: Containing more in depth explanation of restaurant ethos, culture, menu inspiration, team members of unique selling points.
- Menu: Containing current menu proposition of the restaurant, allowing potential customers a view of what the restaurant offers and at what prices. Taking a transparent approach to this will increase customer loyalty.
- Online Booking: Page to enable customers to submit table reservation requests.

- [Site Map](/workspace/ci-milestone-project-1/wireframes/site-map.pdf)

### Skeleton
At this point I began creating proper wireframes, considering how the User will navigate through the site, what content has priority, and interelation of content. I used Balsamiq to create the below wireframes:

 - [Home page on mobile and desktop wireframe](/workspace/ci-milestone-project-1/wireframes/home-desktop-mobile.pdf)
 - [About Us page on mobile and desktop wireframe](/workspace/ci-milestone-project-1/wireframes/about-us-desktop-mobile.pdf)
 - [Menu page on mobile and desktop wireframe](/workspace/ci-milestone-project-1/wireframes/menu-desktop-mobile.pdf)
 - [Online Reservation page on mobile and desktop wireframe](/workspace/ci-milestone-project-1/wireframes/menu-desktop-mobile.pdf)

### Surface
This is the sensory design section of a website, or how it looks, feels and sounds. I wanted the design to be clean and the colour scheme to be light and refreshing. 

#### Colour
As the restaurant is inspired by South American and international street food, I was keen to choose a colour scheme reminiscent of South America. Because of this i chose to use a predominantly blue, yellow and red colour scheme. These colours feature strongly in the flags of South American countries, as well as their sporting colours - e.g. Argentina, Brazil, Colombia and Costa Rica.

Additionally, the colours blue, yellow and red evoke the emotional responses I would like to evoke in potential customers. According to [this article on 99 designs](https://99designs.co.uk/blog/tips/how-color-impacts-emotions-and-behaviors/), the colours I've chosen evoke the following responses;

 - Blue: Safety and Relaxation
 - Yellow: Happy and Spontaneous
 - Red: Passionate and Energised.

 These emotions should help promote the fresh and exciting feel of the street food menu we wish to convey, while exciting potential customers to make a booking.

 Once I'd chosen the colour scheme, I chose to use the sky blue tone found in the Argentinian flag (#74ACDF) as a starting point and input this to [palleton](https://paletton.com/). As i felt this original blue was slightly too pale, I played with the colour until I found a more vibrant blue I felt was fitting to the asthetic feel I wanted. I decided upon using Blue hex code #3BA5B4.

 To complement my colour scheme I chose the 'triad' option on palleton which provided me two supplementary colours, blue and yellow, which I made additional small tweaks to. 
 
 The complete colour scheme provided my palleton is below, including paler/brighter options.

  ![Colour Scheme](design-resources/color-pallete.PNG)

#### Language/Tone 
I wanted the language to reflect the casual and fun atmopshere of the restaurant, so wrote content in line with this. Avoiding technical or formal language where possible.

#### Styling Considerations
Before beginning development, I listed some styling ideas that I felt benefit the website. Majority of these can be seen in the wireframes.

 - Favicon: Desktop and Mobile.
 - Menu: 
    - Card design, which react to mouse hover (transform: Zoom) to add a level of interaction and excitement to products.
    - Ability to download pdf version of menu in printable format for customer convenience.
 - Navigation
    - Sticky
    - Mobile: 'Burger' menu icon, expanding on click.
    - Logo: Returns to top of current page on click.
 - Location: Embed Google Map iframe showing restaurant location.

## Technologies Used
1. HTML
2. CSS
3. [Bootstrap CSS Framework](https://getbootstrap.com/)
4. [Font Awesome](https://fontawesome.com/)
5. [Google Fonts](https://fonts.google.com/)
6. [TinyPNG](https://tinypng.com/) & [TinyJPG](https://tinyjpg.com/): To minimise image file sizes and maximise page load speed.
7. [ResizePixel](https://www.resizepixel.com/) - To manipulate image size and dimensions.
8. [Real Favicon Generator](https://realfavicongenerator.net/) to generate favicons and icons for desktop and mobile usage.
9. [Am I Responsive?](http://ami.responsivedesign.is/) used for responsive design demo in ReadMe summary.

## Features
This section describes how user achiage what they need interacting with the website;

### Exisiting Features
 - **View Restaurant Information** - Users can read the restaurant background and about sections to understand the restaurants culture and atmosphere to expect.
 - **View Restaurant Location** - The home page and footer give the restaurants address and contact details, as well as embedded google map so users can easily see restaurant location.
 - **Contact The Restaurant** - The site footer provides e-mail and phone contact details for the restaurant, so customers can contact the restaurant directly with queries. Additionally the online reservation form has a test input section so customers can provide additional informations on bookings such as dietary requirements or large party numbers.
 - **Book Reservation Online** - allows users to submit an online booking request via filling out the online form. The form does not work currently, as there is not yet a server side component to save submitted information. I've added a bootstrap modal popup to the form, to provide feedback to customers when booking requests are submitted successfully.
 - **View Previous Customer Experiences** - users can view testimonials from prior customers.
 - **Access Restaurant Social Media** - users can find social media profiles for the restaurant in the footer.

### Features to consider implementing in future.
 - Social Media Feed - Instagram, Twitter, Facebook
 - Integration with third party delivery platforms such as deliveroo and uber eats.
 - Booking Form: Provide different booking times across weekends/weekdays to allow varied opening times.
 - Video(s): Video promoting the restaurant, including short interviews with team members and clips of the restuarant during service.
 - Blog: Blog posts to promote seasonal items and changes to the menu.
 - Embedded Ratings: Tripadvisor and Google star ratigns embedded on home page to further promote website brand.

## Testing

### Validation

#### W3 HTML
I validated the HTML with [W3 Validation Service](https://validator.w3.org/). The results can be seen below;
 - [index](design-resources/testing/HTML/before/home.PNG)
 - [about us](design-resources/testing/HTML/before/about-us.PNG)
 - [menu](design-resources/testing/HTML/before/menu.PNG)
 - [reservation](design-resources/testing/HTML/before/reservation.PNG)

 **Errors**
 The reservation form section showed an error at first, this is because as the option is marked as "required", as the first option must either have an empty 'value' attrivute or have no text content. The fix to this is to add a 'disabled value' showing placeholder text.

 **Warnings**
 All pages showed warnings regarding HTML semantics and use of H1's and H2-6's in sections, however upon review I am happy that all headings are relevant and each page has a relevant unique H1. So I decided to enact any changes. 

#### W3 CSS 
I also validated the CSS with the [w3 Validation Service] and it found no errors.

Screenshots for Final Validations passes can be seen below;
 - HTML:
    - [index](design-resources/testing/HTML/after/index.PNG)
    - [about us](design-resources/testing/HTML/after/about.PNG)
    - [menu](design-resources/testing/HTML/AFTER/menu.PNG)
    - [reservation](design-resources/testing/HTML/after/reservation.PNG)
 - CSS: [style.css](design-resources/testing/CSS/css-validation.PNG)

#### Google Lighthouse Audit
I used Google's lighthouse audit to test the website conforms possitively with Googles performance metrics, with the aim for achieving scores of 90 in all areas on desktop.

After intial testing, the performance metric was below 90, while Accessibility, Best Practices and SEO were low 90's. To improve this i carried out the below actions;

**Performance** - Converted all images from .jpg to .webP, which offers improved compression and therefore quicker loading times. I used the website [caniuse](https://caniuse.com/webp), to ensure webp is compliant with all major web browsers, which is is.

**Accessibility** - Added rel="noopener" and rel="noreferrer" to social media links in footer, to avoid passing of any site information to external sites.

**Best Practices** - Added a 'title' to google map iframe, for improved symantics.

**SEO** - Added meta descriptions for all pages providing an overview of page content and intent.

These changes improved all metrics to the below passing scores;

![Google Lighthouse Audit Score](design-resources/testing/google-lighthouse-audit.PNG)

#### Browser & Device Testing
Using the Google Devtools, I tested the website through the following viewports;

- Moto G4
- Galaxy S5
- Pixel 2
- Pixel 2 XL
- iPhone 5/SE
- iPhone 6/7/8
- iPhone 6/7/8 Plus
- iPhone X
- iPad
- iPad Pro
- Surface Duo
- Galaxy Fold

The only issued i found was some issues on Galaxy fold, where the extra thin viewport caused issues with content visuals and overflowing boxes. To rectify this I included an an additional media query to reduce padding of yellow content boxes to 20px left and right, and remove column padding in the opening hours table.

## Deployment

### Github Pages
The site is hosted using GitHub pages, deployed directly from the master branch of GitHub. The deployed site will update automatically as new commits are pushed to the master branch.

To host on GitHub pages you must follow these steps:

1. Go to the project repository
2. Go to the 'Settings' tab
3. Scroll down to the 'GitHub Pages' section and set the source to 'Master Branch'. This turns on GitHub pages for the repository.
4. Reload the page. Scroll back to 'GitHub Pages' section, where the new URL for the reployed site can be found.

Additional information around these steps can be found on the [GitHub Pages Help Page](https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site).

To run a version of the site locally, you can clone this repository using the following steps;

In a code editor of your choice;

1. Enter in Terminal: git clone https://russoakham.github.io/ci-milestone-project-1/
2. To disconnect from original GitHub repository enter in terminal: git remote rm origin.

Additional information around these cloning steps can be found on [GitHub Pages Help Page](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) and [removing a remote](https://docs.github.com/en/github/using-git/removing-a-remote)

## Issues I had to overcome
Overall production of the site was smooth, where I only encountered a few small issues;

- **Home Page Banner**: On the home page, the yellow banner slightly blended into the background due to the backgrounds natural yellow hew. To remove this blending, I added a 'box-shadow' effect via CSS to provide a natural effect border. I liked the effect so much, I've applied this to other elements throughout the site.

- **Yellow Content Box & Team-Card Sizing**: Due to the content of the various boxes being different lengths, the yellow boxes and team-cards would size differently on various viewport sizes. This gave a messy look, as evidenced below;

![Yellow-Content-Box Auto Sized](design-resources/testing/yellow-box-incorrect-sizing.PNG)

To ensure i clean look, I wanted to ensure all elements were uniform in size. To enable this I added a 'min-height' css rule to the '.yellow-content-box' class, plus additional media-queries using bootstrap breakpoints, to ensure uniform height across devices.

![Yellow-Content-Box Auto Sized](design-resources/testing/yellow-box-correct-sizing.PNG)

- **Google Map iframe**: Similar to the yellow-content-boxes, I had to add media-queries to the iframe embedding the google map, to ensure this resized in line with it's partnered yellow content box. As the google map element is sized by the 'padding-bottom' css rule, I had to use this rather than 'min-height'.

- **logos and menu pdf**: As this is a new business, I had to create an original logo and menu. To accomplish this I used [Canva](https://www.canva.com/), which provided templates I was able to adapt. I used the colours as noted under the 'UX' section to ensure they aligned to branding.

- **Favicons**: I used [Real Favicon Generator](https://realfavicongenerator.net/) to create favicon images, for use across windows, iOS and android based devices.
The generator does advise the files be placed directly into the website root, however for file cleanliness I decided to place these in a [sub-directory](assets/images/favicons). After testing, it appears to not have caused an issue for favicons to be working correctly.

- **Team Card Images**: The images on the team card would stretch vertically when viewed on a thin screened device, such as my iPhone XR. This is because the images were under the "card" classes 'display: flex' and 'flex-direction: column" rules. To rectify this, I wrapped the images in their own div and use this as my styling class for the images. 

## Issues still to overcome
- **Online Reservation Form**: Currently the form allows booking for the restaurants static open hours of 12pm-10pm Monday-Sunday. However so as to allow the restaurant to open different hours on different days and also to close for certain days (e.g. christmas), the form needs to be updateded so the available booking slows can be dynamically updated.
To achieve this I would need to implement javascript to the form, which is currently outside my expertise.
Alternatively, I'd advise the client to partner with a third party provider who provide online booking solutions such as [Opentable](https://www.opentable.co.uk/). This could then be directly embedded to the booking page, allow owners to easily update booking availability without the need of developer help and would offboard the need for future development to the third party.

## Credits

### Design and research
The following sites are websites that I used for reference and inspiration:
The following are sites I used for reference and inspiration:
- [Burger Theory](https://burgertheory.co.uk/)
- [Backyard Chicken Company](https://www.backyardchicken.co.uk/)
- [Randy's Wing Bar](https://randyswingbar.co.uk/)
- Colour Selection
    - 99 designs [https://99designs.ie/blog/tips/how-color-impacts-emotions-and-behaviors/]
- Menu Card Format
    - [Nandos](https://www.nandos.co.uk/food/menu/index.html)
in solving technical issues:
- Team Card Format: [Kevin Bourke Milestone 1](https://bourkekev.github.io/ms1-music-school/about.html)

### Technical
The following sites are websites I used to assist in solving technical issues:
- Google Map Embed: [Google Developers](https://developers.google.com/maps/documentation/embed/get-started)
- [Real Favicon Generator](https://realfavicongenerator.net/): For generation of Favicon icons and code.
- [Bootstrap Docs](https://getbootstrap.com/docs/5.0/getting-started/introduction/): For guidance on Bootstrap use and adaptations.
- [CSS-Tricks](https://css-tricks.com/): For implementing CSS effects such as box-shadow.
- [w3Schools](https://www.w3schools.com/): For checking proper syntax of HTML and CSS elements. 
- [Autoprefixer] - For generation CSS browser prefixes.

### Content
All text content on the site was written originally by myself, with the below notes;
- **Customer Testimonals** - Inspired and adapted from [Tripadvisor](https://www.tripadvisor.co.uk/) reviews of various restaurants.
- **About Us** - Adapted from [Burger Theory](https://burgertheory.co.uk/##burgers) about us content.
- **Menu** - Inspired and adapted from items on following restaurant menus;
    - [Burger Theory](https://burgertheory.co.uk/)
    - [Backyard Chicken Company](https://www.backyardchicken.co.uk/)
    - [Randy's Wing Bar](https://randyswingbar.co.uk/)

### Media
The photos and images used for this site were obtained from;
 - **[Canva](https://www.canva.com/)**:
    - Menu Template (Vernon Street)
    - Logo image.
- **[Shutterstock](https://www.shutterstock.com/)**: From the following Photographers
    - Madrugada Verde
    - Sion Hunnuna
    - Cabeca de Marmore
    - StockCreations
    - Olga Moroz
    - DronG
    - Hakin Mhan
**[Unsplash](https://unsplash.com/)**: From the following Photographers
    - Alex Motoc
    - Louis Hansel
    - Jennifer Burk
    - Sheri Silver
    - Jarritos Mexican Soda
    - Proriat Hospitality
    - Klara Kulikova
    - Artharva Tulsi
    - Natalie Vojsner
    - Julia Joppien
    - Fabien Zakaria
    - Vince Fleming
    - Mario: @wondermario
    - Timothy Barlin

### Acknowledgements

 - Thanks to my mentors Anthony Ngene and xxx for their suggestions, time and support.
 - Thanks to those on Slack for reviewing my project and making suggestions:
 - Thanks to my housemates and friends for reviewing the project in their own times.
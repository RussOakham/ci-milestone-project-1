# Milestone 1 - Paco’s Wing Bar - by Russell Oakham

## Project overview

The project is a small website for a restaurant based in Bristol. The main purpose would be to get people interested in booking a reservation at the restaurant. The website promotes that the restaurant is a small independant business, whose menu is inspired by international street food. 

## UX

Overview of UX decisions, structure etc. Examples of websites I have viewed as part of research & UX decisions from it.

![Responsive demo](developer-resources/testing/responsive-demo.png)

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
3. Bootstrap CSS Framework
4. Font Awesome
5. Google Fonts
6. TinyPNG & TinyJPG: To minimise image file sizes and maximise page load speed.
7. [ResizePixel](https://www.resizepixel.com/) - To manipulate image size and dimensions.
8. [Real Favicon Generator](https://realfavicongenerator.net/) to generate favicons and icons for desktop and mobile usage.

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

#### W3 CSS 

#### Browser & Device Testing

## Deployment

### Github Pages

## Issues I had to overcome

## Credits

### Design and research
The following sites are websites that I used for reference and inspiration:

### Technical
The following sites are websites I used to assist in solving technical issues:

### Content

The text for section Y was copied from the Wikipedia article Z

### Media

The photos used in this site were obtained from ...

### Acknowledgements

I received inspiration for this project from X
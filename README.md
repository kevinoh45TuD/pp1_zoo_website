# Central Zoo

## Intro

The purpose of this project is to create a website for a fictional zoo.
The goal of this website was to create it using HTML and CSS.
Below I have outlined different design choices, features of the pages
and what things were used to create this website.

## Table of Contents

1. UX
   - User Stories
   - Site Owner Goals
   - Wireframes
   - Color Palette
   - Font / Icons
   - Imagery
2. Features
   - Navigation Bar
   - Home
   - Animals
   - Gallery
   - Contact Us
   - Footer
   - Extra Pages
   - Future Features
3. Technologies Used
   - Languages
   - Code
   - Font / Icons
   - Media
4. Testing
   - Validator
   - Lighthouse
   - Wave webaim - Accessability testing
   - Manual Testing
5. Deployment
6. Credits
   - Code Institute
   - Media
   - Other

## UX

### User Stories

Here I have outlined some user stories of things the user might want from this website.

- As a user, I want to find out information about Central Zoo.
- As a user, I want to find the opening hours.
- As a user, I want to find out what I can see / do at Central Zoo.
- As a user, I want to learn more about the animals I will see.
- As a user, I want to see photos of animals.
- As a user, I want to contact the zoo about a query.
- As a user, I want to the address for Central Zoo.

### Site Owner Goals

Like with the above section here I have outlined some requirements the site owner might have.

- Attract new potential customers to come to the zoo.
- Find out an issues a user / customer might have, or an issue they have with the website itself.
- Inform user / customers of opening hours.
- Highlight available things to do and see at Central Zoo.
- Provide user with important details in relation to finding or contacting the zoo.

### Wireframes

I created my wireframes using [Balsamiq](https://balsamiq.com)

My initial concept was based on a website for Dublin zoo, this was changed after the wireframe stage to have the website made for a fictional zoo.

- [Home page wireframe](/doc-media/doc-wireframes/wireframe-home.png)
- [Animals page wireframe](/doc-media/doc-wireframes/wireframe-animals.png)
- [Gallery page wireframe](/doc-media/doc-wireframes/wireframe-media.png)
- [Contact page wireframe](/doc-media/doc-wireframes/wireframe-contact.png)

Other things changed after the wireframe but the general layout and color scheme stayed the same.

### Color Palette

My initial color palette was picked using a website called 'Coolors'. I picked 3 different shades of green and 1 shade of yellow/orange.
I wanted to use these types of colors for the website as it would be fitting to the nature based theming of the website.

![Picture of initial color palette](/doc-media/doc-initial-palette.png)

[Link to coolors with palette](https://coolors.co/39ff39-005200-85ff85-dab52e)

I next used a website called ColorSpace to help generate values to make more complimentary shades of green. I used the original dark green hex to base the other shades on.

![Picture of final color palette](/doc-media/doc-origin-palette.png)

[Link to colorspace with green generation](https://mycolor.space/?hex=%23005200&sub=1)

To find a new yellow/orange color I used the same website with initial color set to the new shade of green '#579A47' and found a fitting shade under the 'Skip Shade' section.

![Picture of new yellow/orange color](/doc-media/doc-alt-palette.png)

With the final color palette chosen I used ContrastGrids to check each colors contrast with each other.

![Picture of contrast grid](/doc-media/doc-contrast-palette.png)

Here is the final color palette together using Coolors once more:

![Picture of final color palette on Coolors](/doc-media/doc-final-palette.png)

### Font / Icons

I used [Google Fonts](https://fonts.google.com) to source the fonts used for this website.

For headings and website title I used [Oswald](https://fonts.google.com/specimen/Oswald)

For general text and nav bar I used [Varela Round](https://fonts.google.com/specimen/Varela+Round)

### Imagery

All the photos and video on my website were found on [Pexels](https://www.pexels.com) except for the map image.
The link to each piece of media can be found in the credits section.

I chose to use releastic images for my website as I felt the imagery needed to be similar to what you might see if you go to this fictional zoo.

![Picture of Lion](/assets/images/lion-1.jpg)

I also wanted to pick images and videos that had a lot of greenery. This would match well with the color palette of my website.

[Back to top](#central-zoo)

## Features

### Navigation Bar

![Picture of full nav-bar](/doc-media/nav-1280w.png)

The navigation bar features the title of the website along with anchors to the 4 main pages that will be discussed below.
Clicking the title or 'home' on any page will have the same function of bringing the user to the home page / index.html

![Picture of highlighted nav-bar](/doc-media/header-640w.png)

When on a device using a mouse the navigation elements will gain a border based on which one you are hovering over.
The color will also change based on which page you are currently on.

![Picture of mobile nav-bar closed](/doc-media/navclose-480w.png)

When on a small / mobile screen the navigation bar will feature the title of the website and a burger icon to open the other navigation links.

![Picture of mobile nav-bar open](/doc-media/navopen-480w.png)

Clicking on the burger icon will reveal to the user the remaing anchor links to the other pages.

### Home

The home page features 3 main things:

- General Info, text to welcome the user and explain the website.
- Opening hours, showing the user when the zoo will be open on different days.
- Map, an image showing what attractions are featured at the zoo and where they are in relation to other things.

![Picture of home screen large](/doc-media/home-1280w.png)

On a larger screen size the general info and opening hours section will be feature horizontally.

![Picture of home screen mobile](/doc-media/home-480w.png)

Whereas on a smaller / mobile screen they will be featured vertically with general info coming first.
Both variations have the map featured last.

### Animals

The animals page presents users with information about 3 animals featured at Central Zoo. A lion, an orangutan and a giraffe.
Each animal is given a title, an image and piece of a text with facts about the animal.

The information found in the text was sourced from [KidzSearch](https://wiki.kidzsearch.com/wiki/Main_Page).
Links for each animal specifically can be found in the credits section.

![Picture of animal page large](/doc-media/animals-1280w.png)

On a larger screen size the image for the animal alternates from left of the text to right going down the page.

![Picture of animal page mobile](/doc-media/animals-480w.png)

On a smaller / mobile screen size the order of information is in a column. Featuring title -> image -> text

### Gallery

The gallery page features additional pieces of media for Central Zoo.
This page contains 1 video and 6 images.

![Picure of gallery page large](/doc-media/galleryphoto-1280w.png)

With a larger screen size the 6 images will arrange to 3 columns and 2 rows.

At a medium screen size the images will arrange to 2 columns and 3 rows.

![Picture of gallery page mobile](/doc-media/galleryphoto-480w.png)

At a smaller / mobile screen size the images will arrange into a single column and alternate between tall and short images.

![Picture of orangutan video](/doc-media/galleryvideo-480w.png)

Regardless of screen size the video is featured at the top of the page directly under the header.
The video element fills the entire width of the screen. Users have the controls to play and fullscreen the video.
The video starts mute, although it doesn't have audio it is best practice to default the video to mute.
The video will not play till the user starts it, but as it is a short video it is set to loop once it finishes.

### Contact Us

![Picture of contact page large](/doc-media/contact-1280w.png)

![Picture of contact page mobile](/doc-media/contact-480w.png)

### Footer

The footer of the website page remains consistent regardless of screen size.

![Picture of footer large](/doc-media/footer-1280w.png)

It features 3 icons that when clicked on will open a new tab to the respective social media website.
The three icons featured are Facebook, Twitter and Youtube.

![Picture of highlighted footer icon](/doc-media/footer-64w.png)

On devices that are using a mouse the color of the footer icon changes when hovered over.

### Extra Pages

This website features two additional pages. A thank you screen for when the user submits a contact form and a 404 page incase the run into an error.

![Picture of thank you page large](/doc-media/thankyou-1280w.png)

The thank you page is only visible if the user submits a contact form, alternatively it can be found by inputting the page address directly.
[Link to thank you page](https://kevinoh45tud.github.io/pp1_zoo_website/thank-you.html)

The user will be prompted to go to another page on the website. They will also have an instant link to return to the home page.

![Picture of 404 page large](/doc-media/404-1280w.png)

The 404 page is only visible if the user runs into an error while on the central zoo website. Alternatively it can be found by inputting the page address directly.
[Link to 404 page](https://kevinoh45tud.github.io/pp1_zoo_website/404.html)

The user will be prompted to return to the home page which they will have an instant link for.

### Future Features

1. Home page interactable map:
   - First option would be to have the map remain how it is currently but add the functionality to click parts of the map to go to different pages on the site.
   - Second option would be to replace the map with one that embeds something like Google maps to find the location of the zoo itself.
2. Animal page update:
   - Additional animals talked about. Currently there is 3 featured, there could easily be 6+ on the animal page.
   - Interactions and animations could be added to this page also to make it more engaging for users.

[Back to top](#central-zoo)

## Technologies Used

### Languages

- This website was created using both HTML and CSS languages.

- W3schools was used to reference the documentation for both HTML and CSS [W3schools](https://www.w3schools.com)

### Code

- Github was used to both manage my repository and host my website using the pages functionality [Github](https://github.com)

- Codeanywhere was used as a cloud-based IDE [Codeanywhere](https://app.codeanywhere.com/)

### Font / Icons

- Google fonts was used for this website [Google Fonts](https://fonts.google.com)

- Font Awesome was used for the icons feature on the Footer and Nav Bar sections [Font Awesome](https://fontawesome.com)

- Faviconer was used to create an ICO file for the favicon icon [Faviconer](http://faviconer.com)

- FireAlpaca software was used to create the art for the favicon icons [FireAlpaca](https://firealpaca.com)

### Color Palette

- Coolors was used to initially pick colors for websites color palette [Coolors](https://coolors.co)

- ColorSpace was used to generate updated color palette based on initially picked colors [ColorSpace](https://mycolor.space)

- EightShapes Contrast Grid was used to test contrast of color palette [EightShapes](https://contrast-grid.eightshapes.com)

### Media

- Pexels was used to source free to use photos and video for both the 'Animals' and 'Gallery' pages [Pexels](https://www.pexels.com)

- Compressor was used to lower the file size of the photos used [Compressor](https://compressor.io)

- FreeConvert was used to lower the file size of the video used [FreeConvert](https://www.freeconvert.com)

- Freepik was used to source the image used for the map on the Home page [Freepik](https://www.freepik.com)

- KidzSearch was used to source information for the text sections of the animals page [wiki.Kidzsearch](https://wiki.kidzsearch.com/wiki/Main_Page)

[Back to top](#central-zoo)

## Testing

### Validator

#### W3C CSS

[Link to CSS validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkevinoh45tud.github.io%2Fpp1_zoo_website%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

#### HTML validator

- [Link to HTML index page validator](https://validator.w3.org/nu/?showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fkevinoh45tud.github.io%2Fpp1_zoo_website%2Findex.html)
- [Link to HTML animals page validator](https://validator.w3.org/nu/?showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fkevinoh45tud.github.io%2Fpp1_zoo_website%2Fanimals.html)
- [Link to HTML gallery page validator](https://validator.w3.org/nu/?showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fkevinoh45tud.github.io%2Fpp1_zoo_website%2Fgallery.html)
- [Link to HTML contact us page validator](https://validator.w3.org/nu/?showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fkevinoh45tud.github.io%2Fpp1_zoo_website%2Fcontact-us.html)
- [Link to HTML thank you page validator](https://validator.w3.org/nu/?showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fkevinoh45tud.github.io%2Fpp1_zoo_website%2Fthank-you.html)
- [Link to HTML 404 page validator](https://validator.w3.org/nu/?showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fkevinoh45tud.github.io%2Fpp1_zoo_website%2F404.html)

### Lighthouse

Screenshot of Lighthouse for index.html on Desktop:

![Lighthouse screenshot index desktop](/doc-media/doc-test-images/light-home-pc.png)

[Lighthouse screenshot index mobile](/doc-media/doc-test-images/light-home-mobile.png)

Screenshot of Lighthouse for animals.html on Desktop:

![Lighthouse screenshot animals desktop](/doc-media/doc-test-images/light-animal-pc.png)

[Lighthouse screenshot animals mobile](/doc-media/doc-test-images/light-animal-mobile.png)

Screenshot of Lighthouse for gallery.html on Desktop:

![Lighthouse screenshot gallery desktop](/doc-media/doc-test-images/light-gallery-pc.png)

[Lighthouse screenshot gallery mobile](/doc-media/doc-test-images/light-gallery-mobile.png)

Screenshot of Lighthouse for contact-us.html on Desktop:

![Lighthouse screenshot contact us desktop](/doc-media/doc-test-images/light-contact-pc.png)

[Lighthouse screenshot contact us mobile](/doc-media/doc-test-images/light-contact-mobile.png)

Links to find screenshot for Lighthouse on 404.html and thank-you.html on Desktop:

- [Lighthouse screenshot thank you desktop](/doc-media/doc-test-images/light-thank-pc.png)
- [Lighthouse screenshot 404 desktop](/doc-media/doc-test-images/light-404-pc.png)

### Wave webaim - Accessability testing

- [Link to WAVE Home](https://wave.webaim.org/report#/https://kevinoh45tud.github.io/pp1_zoo_website/index.html)
- [Link to WAVE Animals](https://wave.webaim.org/report#/https://kevinoh45tud.github.io/pp1_zoo_website/animals.html)
- [Link to WAVE Gallery](https://wave.webaim.org/report#/https://kevinoh45tud.github.io/pp1_zoo_website/gallery.html)
- [Link to WAVE Contact Us](https://wave.webaim.org/report#/https://kevinoh45tud.github.io/pp1_zoo_website/contact-us.html)
- [Link to WAVE Thank you](https://wave.webaim.org/report#/https://kevinoh45tud.github.io/pp1_zoo_website/thank-you.html)
- [Link to WAVE 404](https://wave.webaim.org/report#/https://kevinoh45tud.github.io/pp1_zoo_website/404.html)

### Manual Testing

| Feature being tested | Expected Outcome   | Testing Performed  | Actual Outcome     | Result (Pass or fail) |
| -------------------- | ------------------ | ------------------ | ------------------ | --------------------- |
| enter details here   | enter details here | enter details here | enter details here | enter details here    |

[Back to top](#central-zoo)

## Deployment

My website was deployed using 'Github Pages'.

Steps taken to achieve this:

1. Go to repository page
2. Click 'Settings'
3. Click 'Pages'
4. Select 'main' branch to deploy from

[Back to top](#central-zoo)

## Credits

- A special thanks to my mentor Matt Boden for his assistance throughtout the project! [MattBCoding](https://github.com/MattBCoding)

### Code Institute

- Code Institute template used for repository [Template](https://github.com/Code-Institute-Org/ci-full-template)

- Code Institute learning modules used to learn different aspects of HTML/CSS [Code Institute](https://codeinstitute.net/ie/)

### Media

#### Animal Page

- Lion picture used on 'Animal' page [Lion photo](https://www.pexels.com/photo/close-up-photo-of-lion-1598377/)
- Orangutan picture used on 'Animal' page [Orangutan photo](https://www.pexels.com/photo/orangutan-eating-fruit-near-funny-baby-primate-hanging-on-liana-825595/)
- Giraffe picture used on 'Animal' page [Giraffe photo](https://www.pexels.com/photo/selective-focus-photography-of-giraffe-head-797643/)

- Lion information from Kidzsearch [Lion text source](https://wiki.kidzsearch.com/wiki/Lion)
- Orangutan information from Kidzsearch [Orangutan text source](https://wiki.kidzsearch.com/wiki/Giraffe)
- Giraffe information from Kidzsearch [Giraffe text source](https://wiki.kidzsearch.com/wiki/Orangutan)

#### Gallery Page

- Elephant picture used on 'Gallery' page [Elephant photo](https://www.pexels.com/photo/photo-of-an-elephant-2499271/)
- Panda picture used on 'Gallery' page [Panda photo](https://www.pexels.com/photo/photo-of-a-black-and-white-panda-hanging-on-a-tree-6967903/)
- Parrot picture used on 'Gallery' page [Parrot photo](https://www.pexels.com/photo/a-blue-throated-macaw-perched-on-a-tree-branch-12715213/)
- Rhino picture used on 'Gallery' page [Rhino photo](https://www.pexels.com/photo/rhinoceros-resting-near-green-trees-in-zoo-4394473/)
- Tiger picture used on 'Gallery' page [Tiger photo](https://www.pexels.com/photo/dangerous-staring-tiger-19334636/)
- Zebra picture used on 'Gallery' page [Zebra photo](https://www.pexels.com/photo/close-up-shot-of-a-zebra-7266345/)

- Orangutan video used on 'Gallery' page [Orangutan video](https://www.pexels.com/video/orangutan-stretching-in-a-forest-7710027/)

#### Map

- Vector art of map used on 'Home' page, Image by rawpixel.com on Freepik [Map image](https://www.freepik.com/free-vector/illustration-zoo-park-map_2922222.htm#query=zoo%20park%20map&position=1&from_view=keyword&track=ais&uuid=1bc24b52-0c51-4f53-aa60-72ca22b520f8)

### Other

- An article on GitHub was used to help with creating this README doc [Article](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- An article outlining a CSS fix for error created from nav toggle [Article](https://css-tricks.com/inclusively-hidden/)
- An article used to help with creating more responsive site images [Article](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

[Back to top](#central-zoo)

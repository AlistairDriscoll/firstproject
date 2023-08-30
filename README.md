![Ally Pally's Logo](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/logo-pic.png)

# Project 1- HTML and CSS
This is a website for a cafe called Ally Pally's. It is a live music venue that sells a variety of food and alcoholic drinks.

## Requirements
The website was desinged so the user can find out everything they need to know about the cafe. It has an intoductory paragraph that talks about the emphasis of live music in the establishment and the user can go on further to find out what it has going on through the week, the opening and closing times, what food and drinks it serves and their times, and it's prices. There is also information about it's location, phone number and social media links in the footer, and if the user wants to find out more about our events or any other queries then there is a contact page that has a form they can fill out.

The website can be accessed through this [link](https://alistairdriscoll.github.io/firstproject/)

![Responsivness picture](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/responsiveness-pic.png)

## Features

### Header
The header is near enough the exact same code accross all pages which has the name as a h1 in big contrasting letters to the background picture. The background picture, like all others in the project is a closeup picture of a musician playing their instrument. I deliberately chose all pictures to have the musician facing away from the camera, to accent the fact that they are playing to a live audience to emphasise that the establishment is a live music venue. I chose the guitar as the first picture because the color scheme came from me choosing a shade from the middle of the guitar and finding matching colors after to go with it. 

The H1 in the middle of the header which displays the name of the cafe is written in a font I found online called Barriecito. I chose this font because I knew the rest of the website a lot of the time would have darker sort of moodier colors to suit the whole jazz aspect of the cafe so I wanted to use something more casual and friendly for the headers and other important parts.

-The nav bar is on the bottom of the header, to position it at the top of the page at all times. The different links are spread across the navbar:
    +The Homepage hyperlink is a link to take you to the home page of the website where the user can find out more about the cafe, it's events and what it has going on.
    +The Menus hyperlink takes you to where the menus are, and the Contact link takes the user to a page with a contact form to fill out.

-The links all have a hover effect added to emphasise to the user that they can be interacted with.

![Navigation bar](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/navbar.png)



## The Homepage

The homepage, or the index.html page starts with an introductory 'what we're about' section informing the user about the cafes emphasis on live jazz music, and what to expect on some of the nights in the week. It also has it's opening times in bold text on another line of the page to mark it out as important information that the user therefore will not miss.

The 'on this week' section that follows has a picture of the highlight act of the week, a local band with a picture to the left of a desktop screen or on the bottom of a phone screen, and a description of the band and more bold text to emphasise when the doors open for the event. Another link is in this section which invites the user to the websites contact page if they are interested in attending.

![index.html main content](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/index-page-pic.png)

### The footer

The other mutual feature between all pages is the footer, which has links to the cafes social media pages. Code is included to open up a new tab for the links so the customer will not leave the website, and the links just take you to the main pages of the websites as the cafe is fictitious and doesn't actually have any social media pages. An address and contact number is also provided in the footer thus giving all the user all the important information about the cafe, including the opening times, all of the events of the week, address and contact number by the time they have read through the first page, should they wish to get in touch or visit.


![footer picture](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/footer-pic.png)

## Menus page

The menus page has a list of all the different menus, with the times we are serving the food written in their headers. Flex is used to arrange them in a neat and aesthetically pleasing way with the pictures rounded off with a 30px radius which is uniform with all other img elements used in the website. I added another salmony color to the backgrounds of all the divs to add further contrast in the website.

![First two menu divs](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/first-menu-divs.png)
![Third menu div](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/third-menu-div.png)
![Penultimate menu divs](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/penultimate-menu-divs.png)
![Final menu divs](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/bottom-menu-divs.png)

## Contact page

The main content of the contact page consists of just a form for the user to fill out. The mandatory fields are the name input so we know who we are corresponding with, the email input so we can reply back, and the text area for the user to add additional information. the form has a maximum width so that the background image will not be distorted or repeat itself as it would if it went to the full width of a computer screen. The user can pick a subject from the checkboxes but doesn't need to in order to be able to send the form off. Due to this only being an HTML and CSS project, the method has been set to "get" and not "post" as it is not actually sending off the information to be dealt with. The two buttons are deliberately in contrasting colours to eachother so that it is stressed to the user that they have completely different functions, and they once more have hover classes that change the colour. The submit button will then take the user to another page which gives them a thank you message and informs them that they will be responded to within 48 hours. A link will be there for the user to press here to take them back to the home page.

![Contact form](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/contact.form.png)
![Sent form page](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/sent-form-message.png)


## Technologies used

- HTML founded the structure of the site.
- CSS was responsible for the look and colouring of the site.
- CSS flexbox was used to arrange the items correctly on their pages.
- Balsamiq was used to sketch out how the website would look.
- VS Code was used to code out the entire project.
- Git and Github were used to save the project and upload it to a cloud

## Design

![Color scheme](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/color-scheme.png)
the color black was also used along with #f24a2e which is the more salmon kind of color that was mentioned earlier. The whole color scheme started with me using an eye dropper website to select a shade of brown from the guitar in the header. I then went to an AI color palette generater and locked it in the middle. I then kept refreshing the color palette until the generater had made darker and lighter shades to my liking, locking them in as I go so it was more likely to choose more appropriate colors as we went on. As mentioned before I thought that darker colors a lot of the time such as the dark purple background would be more fitting of a place that has a lot of jazz music.

## Typography

Only two font families were used throughout the website. Either font-family: 'Open Sans', Arial, sans-serif; for the more general stuff such as any p elements. It was actually put into the body element of the HTML in CSS making it the standard then a class with font-family: 'Barriecito', 'Brush Script MT', cursive; was used in overriding classes for other more important elements in the website such as h1-h3, and some hyperlink tags in the footer. As previously stated Barriecito was chosen for its more fun casual sort of nature that would counteract the darker moodier tones of the color scheme in places.

## Testing

The website was tested out on different browsers (Google Chrome, Microsoft Edge and Mozilla Firefox) and on all counts was found to be responsive. An above picture shows how the website would look on different devices as shown on a website called 'Am I Responsive?' where one can see what their product looks like on phones, tablets laptops and bigger computer screens.

### Accesibility

Lighthouse scoring for index.html can be seen here ![index.html lighthouse pic](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/index-lighthouse.png)

Lighthouse for menupage.html ![menupage.html lighthouse](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/menus-lighthouse.png)

Lighthouse for contactpage.html ![contactpage.html lighthouse](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/contact-lighthouse.png)

### Validation

index.html validation: 
![index validation](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/index-page-validation.png)

The only problem with the menus validation is that it seemed to think the 0 digit was supposed to be a p, it doesn't intefere with the code so I just left it.
 ![menu validation](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/menu-page-validation.png)

With the contactpage.html validation I realised I accidentally assigned required values to labels as well as giving the email label an email type, I think due to the lines being so close together I might have gotten mixed up. I also thought there was such this as a 'name' input when I really should have put "text".

![contactpage.html validation](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/contact-page-validation1.png)

![contactpage.html validation 2](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/contact-page-validation-completed-code.png)

I then amended the code.

![contactpage.html validation complete](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/contact-page-validation-complete.png)

With the CSS validation, I realised after experimenting with color contrast I accidentally put the background color to a background image and the color of the text as the same, this was then amended. I also struggled at first with pointer-events as my hover classes were not working at first.

![css validation](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/css-validation-problems.png)

![more css validation](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/css-validation-problems2.png)

![finished css validation](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/css-validation-solved2.png)

### Bugs

bugs were that I got stuck in a rabbit hole trying to fix the hover functions for the sentform homepage button. I eventually solved this with devtools.

### Responsiveness

![index responsivity testing](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/index-responsivness.png)
![Menu responsivity testing](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/menu-responsivness.png)
![Contact responsivity testing](https://github.com/AlistairDriscoll/firstproject/blob/main/assets/images/readme-pics/Contact-responsivness.png)

## Deployment

This website is deployed on Github. To deploy go to settings, select the main branch, and press save.

- The live link can be found here ![Ally Pallys](https://alistairdriscoll.github.io/firstproject/index.html)

## Credits

### Content

The button classes on my form with opposing colors to suggest a completely different usage were inspired by the coders coffeehouse form that I did in my Code Institute course content.

The idea to have another page with a 'thank you for getting in touch' message after completing the contact form was inspired by my mentor Julia's Animal shelter page, along with what to put in my aria label messages.

### Media

Alot of the images used were taken from a website called unsplash, which seemed to be the best provider of useful and specific stock photos out of all the ones I tried.

![The websites icon](https://static.vecteezy.com/system/resources/previews/002/215/990/original/saxophone-icon-musical-instrument-for-jazz-golden-musical-instruments-concept-classical-music-jazz-concert-performance-flat-cartoon-illustration-isolated-on-white-background-vector.jpg)


![Header picture](https://images.unsplash.com/photo-1633485666359-f93a2a27f59c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80)

![Sentform piano picture](https://unsplash.com/photos/0PFCxy_n9F8)

![Double bass picture](https://unsplash.com/photos/vSws0g1KjxI)

![Hyde park brass picture](https://hydeparkbrass.com/)

![Saxophone picture](https://unsplash.com/photos/1ayBjduURMo)

![Beers picture](https://unsplash.com/photos/a-row-of-beer-glasses-sitting-on-top-of-a-wooden-tray-vt0O0Av96R4)

![Cocktails picture](https://unsplash.com/photos/dmkmrNptMpw)

![Wines Picture](https://images.unsplash.com/photo-1554381401-dc595be1d842?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=391&q=80)

![Olives picture](https://images.unsplash.com/photo-1683543121487-b718fa4f8bd1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1074&q=80)

![Pancakes picture](https://images.unsplash.com/photo-1528207776546-365bb710ee93?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80")

![Burger picture](https://images.unsplash.com/photo-1460306855393-0410f61241c7?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1173&q=80)

![Roast dinner picture](https://images.unsplash.com/photo-1635897411141-7bd2b9c6ab16?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1074&q=80)



### Tools

I used cloudconvert.com to convert avif files to png

I used tingpng.com to compress the converted png images to use in my project.
# Summit Events

## Table of contents

* [Introduction](#introduction)
* [Technologies Used](#Technologies-Used)
* [Project Features](#Project-Features)
* [Project Structure](#Project-Structure)
* [Testing](#Testing)
* [Accessibility](#Accessibility)
* [Installation and Setup](#Installation-and-Setup)
* [Deployment](#Deployment)
* [Attribution](#Attribution)


## Introduction

Summit Events is a static front-end website desinged to function as a first port of call for anyone wishing to book an activity through Summit Events or find out more information about the services they offer. It is designed to be simple, accessible, and fully responsive, ensuring users have a seamless experience whatever device they're browsing from - mobile or desktop.

Image insert

The website features:

* A Home page with an introduction sections to each part of the business, with links to more information and a booking form.
* A review section with two customer reviews about different aspects of tbe business.
* A contact section with the business address, phone number and email address
* The site uses HTML5, CSS3, and Bootstrap for responsive layout and styling.

## Technologies Used

* HTML5: Structuring the website and content.
* CSS3: For styling and layout.
* Bootstrap: A front-end framework used for its grid system and responsive design components, ensuring a mobile-friendly site that looks great across various screen sizes.
* Google Fonts: I used fonts Montserrat, and Rock Salt to ensure good typography and readability. Montserrat was chosen for its clean, aesthetic, and Rock Salt for a more friendly personable appeal.

## Features
  
* Multi-page website with three key sections: Home, Booking, and Contact.
* Interactive bootstrap cards with off-canvas sidebars section for the four main activities run by Summit Events, Mountain Days, Forest Days (Bushcraft), Water Days, and Target Sports.
* Reviews about customer's bushcraft and paddling experiences
* Images of the activities with descriptions and links to further information and a booking form. 
* A Contact section with a business address, and phone and email links so that visitors can choose how they contact us.
* Responsive layout ensuring compatibility with both mobile and desktop devices.

## Project Structure

### Files and Folders:

* index.html: The Summit Events homepage containing information about the activities run by the company and links to the booking form for each side of the business. Also featuring a reviews section, photos of activities and a contact section with various methods of contacting the company.

* booking.html: The Summit events booking form for all aspects of the business, complete with a comments box to cater for specific questions or requirements customers may have.

* success.html: Confirmation page with a message that the booking form or query was successfully submitted.

* assets/images:
  - archery.jpeg The target Sports image below the review section.
  - bushcraft.jpeg The Forest days card image.
  - bushcraft2.jpeg The Forest days image below the review section.
  - canoe.jpeg The Water Days image below the review seciton.
  - mountainsunset.jpeg The Mountain Days image below the review section.
  - river.jpeg The Water Days card image
  - rocks.jpeg The Mountain Days card image.
  - target.jepg The Target Sports card image.

* assets/css:
  - Contains the website's custom styles.
 
## Testing

##### HTML Validation:

<img width="1270" alt="Screenshot 2024-12-09 at 21 44 14" src="https://github.com/user-attachments/assets/8d810d58-6f57-4c35-bcd5-1bb413f41309">

##### CSS Validation:

<img width="1277" alt="Screenshot 2024-12-09 at 21 36 37" src="https://github.com/user-attachments/assets/15fc3281-2cd9-4d23-93bf-4bb0b50938ab">


### Lighthouse Validation:

##### Home Page

<img width="491" alt="Screenshot 2024-12-09 at 21 53 00" src="https://github.com/user-attachments/assets/8c73d32a-8920-4f29-98be-1d5226fec90b">


##### Booking Page

<img width="489" alt="Screenshot 2024-12-09 at 21 53 47" src="https://github.com/user-attachments/assets/415f91b0-9e55-4a0c-9ade-11fb8b391fe5">


##### Success Page

<img width="487" alt="Screenshot 2024-12-09 at 21 54 38" src="https://github.com/user-attachments/assets/f74431b7-8568-4892-8d98-db3efb8eeb24">


## Accessibility

To make the site as accessible as possible, the following features have been implemented:

#### Responsive Design
The site is designed to be fully responsive, ensuring that it works well on phone, tablet, and desktop devices.

#### Semantic HTML
Proper HTML tags \(e.g., \<header\>, \<footer\>, \<section\>, \<nav\>\) are used to create a logical structure and improve readability for screen readers.

#### Alternative Text for Images
All images include descriptive alt text to ensure screen readers can relay information effectively to visually impaired users.

#### ARIA (Accessible Rich Internet Applications) Attributes
ARIA labels and roles were added to improve the accessibility of the navigation menu, further information buttons, and social media links.

#### Colour Contrast
High contrast between text and background colours is maintained to ensure readability for users with low vision or colour blindness. For example, the text colour contrasts well with the background colour on the nav bar and activity cards \(Mountain Days, Forest Days, etc\)
#### Forms and Labels
All form fields have clear and labels to ensure that they are understandable for screen readers.

#### Keyboard Accessibility
The website is fully navigable using the keyboard. Users can easily navigate between interactive elements on the nav bar, information and booking buttons, closing buttons, social media links and form fields using the Tab key.

#### Wave Chrome Accessibility Tool
The WAVE Web Accessibility Evaluation Tool is a free browser extension that helps identify and fix accessibility issues on web pages.

\*\*Images to follow

## Installation and Setup

### To set up the project locally, follow these steps:

1. Clone the repository:
git clone https://github.com/bertellis/Summit.git

3. Open the project folder in your preferred code editor or file browser.
4. Open index.html, quitlit.html, or contact.html in your browser to view the respective pages.
5. Bootstrap, the necessary CDN links are included in the <head> section of the HTML files.
6. Google Fonts are included for custom typography.

## Deployment

This project was regularly pushed to github from the workspace throughout its design, with comments describing each commit.

The project is deployed on GitHub Pages and can be accessed at:
https://bertellis.github.io/Summit/

## Attribution

Images: All images are sources from google image searches using free-to-use images.


Bootstrap is used for responsive design. Attribution can be found in the code.


Google Fonts: Custom fonts Montserrat, and Rock Salt are used for better typography, sourced from Google Fonts.


Thank you to Spencer Bariball for his help and advice on this project.


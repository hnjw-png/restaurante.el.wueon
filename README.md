![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


Project Readme:

The website 'Restaurant El Wueon' is a four-page website with the purpose to encourage new customers to a new restaurant. It consists of four pages; 'homepage', 'contact us','our story' and 'book table'.

This website is intended to give information about the services the restaurant provides, including contact information, location, booking form, fun facts, motto, as well as many photos of the restaurants food. 

The page will be color coordinated with a brown background (representing the color of food)  

The website is responsive and changes according to screen sizes.

The target audience is new customers, and returning ones of all ages. This is a family friendly restaurant, and will attract people interested in homemade chilean cuisine.

![ami screenshot](https://user-images.githubusercontent.com/120515252/211731563-c37e7a0a-548e-4401-a5ae-b0fbf31ef5e6.jpg)


Features:

Nav bar:

There is four links to the top right of the screen on every screen. These will direct you to the page of the website you see. (e.g.Home to Home. Our story to the page our story.) You do not need to use the back or forward button on the browser, the links will take you where you need to go.

![top nav bar](https://user-images.githubusercontent.com/120515252/211733071-28c7fcc1-27fb-4595-b46b-2ef5c3680a41.jpg)

When you hover over each nav button it be highlighted with a black circle, with the page name in white still visable.


Header Logo:

You can click the header logo name and be directed back to the homepage, and this works on all pages. When you hover over the homepage name the underlines and changes color, so you know its navigation button.


![header screenshot](https://user-images.githubusercontent.com/120515252/211731823-9e9fd360-f74a-498e-bb2a-0756e8d2b9fa.jpg)



Homepage:

The first section of the homepage will include a introduction about restaurant El Wueon and the experience the restaurant wants to provide.
![homepage start](https://user-images.githubusercontent.com/120515252/211731969-3a6c25b0-0df7-4ab6-b9c7-6aa5f85b3ae5.jpg)


In the second section there will be three circluar images of food, thereafter opening times in a table, then a another circular image of food and then the location of the restaurant.

![screenshot open](https://user-images.githubusercontent.com/120515252/211732014-02ae6aa0-52a4-44dc-a6ce-86b30da78394.jpg)

Contact us page:

This page will include a table with information for the restaurant including email and phone number.
It will have a range of food images in circular shape, this will be located below the contact details.

![screen contact](https://user-images.githubusercontent.com/120515252/211732051-5494d9fb-bc1f-468a-a701-2aa7aff4f5d6.jpg)

In the section there is a fun facts section, explaining the meaning of the word wueon.
Underneath there is a list of words that are only used in Chile and the translation in english.

![screenshot fun facts](https://user-images.githubusercontent.com/120515252/211732076-09ffc1d3-c7fb-419b-9c52-a9c3bfdb42b8.jpg)

This page correlates with the rest of the website. (font, color, background, navigation, header and footer)

###Our Story Page:

This page will include a section about the story of the restaurant. This is a personal statement from the owners that will explain a little more to customers about the food style and motto of the restuarant. In between the text there will be a circular image of food. 

![screenshot our story](https://user-images.githubusercontent.com/120515252/211733317-7d34a1e9-5da0-4c88-b418-46bfa6ff8c19.jpg)



Below the our story section there is three circular images of food.

![screen shot botom our story](https://user-images.githubusercontent.com/120515252/211732198-54ffae47-b784-4fa7-a00a-40c08f485ea5.jpg)


This page correlates with the rest of the website. (font, color, background, navigation, header and footer)

Book table page:

This page will include a form that customers can use to request to book a table. 
Here they can enter first name, last name, date and how many; each input is set to the correct input. For example you can only type a email address for the email input. 

![screen shot book table](https://user-images.githubusercontent.com/120515252/211732235-6fcaeed9-f5c5-460e-9a5a-2bd5e63c275b.jpg)


Underneath the booking form, there is three circular images of food.

![bottom book tbale screen](https://user-images.githubusercontent.com/120515252/211732266-1dc9184d-ab32-4ea2-9678-9c8a21ded852.jpg)

Footer:

Footer has external links to facebook and instagram.


![footer](https://user-images.githubusercontent.com/120515252/211733628-cc8645f6-0af0-4cf1-a0f7-15270b045df1.jpg)


This page correlates with the rest of the website. (font, color, background, navigation, header and footer)

Features left to implement:

Add another page, to showcase the menu. This will consist of images of each dish and information on what it contains as well as the price.

Validation:

Testing:
1. I have tested all navigation buttons and they all function on each page. When you over over a selected nav button a black colored circle appears behind it to show which page your about to click on.

2. I have tested that the header navigation bar always directs you back to the homepage. When you hover over the header the underline changes color to brown, to indicate its a functional navigation button.

3. I have tested that the website functions on all screen sizes, I did this by using media queiries to adjust sizes of the text and header, as well as the nav keys.
4. On smaller screens the images with appear in a triangular formation or a verticle line. On larger, in a horizantal straight line format.
The rest of the website function well without adding any more media queiries.

5. Images through-out the webpage follow the same structure by all being circular, as well as there style and placement. Each pages contains three images or more images, in a fashioned eye-catching order. All the images have a alt attribrute, that tells you specifically what the photo is of. 

6. The form is functional, you cannot submit without filling out all of the the questions. You can only right the correct input into the input boxes, e.g, the email address box, can only contain a email address, the requested date is only a date and so on.

7. All headings, paragraphs, forms, tables follow the same styling throughout.


nfixed testing  bugs:

1.Footer keep floating towards the main content on the contact us page. Tried mulitple attempts.
I fixed this with adding a bit more content on the contact us page, this worked nicely and helped the website correlate with the rest of the website. 

I am continuing to research into, how to place the footer at the bottom of the page, when there is less content. 

I tried adjusting the margin top, but this was diffcult to maintain across different page sizes. As well as the positioning tools.

2.when submiting form there it reports a error 501, unsupported method(POST), this is due to there being nowhere to send the information. 

I researched into where I can send such information and discovered 'php'. I then added a php file to my workspace, but this made the form save as a file directly to my computer. 

I decided to remove this function, as this outcome is un-needed for the user. 

I will continue to look further into the issue.


Validator Testing

No errors found in HTML W3C validator.
No errors found in CSS JIGSAW validator

lighthouse testing

Homepage: Accessibility, 100.

![homepage lighthouse](https://user-images.githubusercontent.com/120515252/211732501-7dcdd4a9-7616-4c0f-bb0f-782bff05b02a.jpg)


Contact us: Accessibility, 100.

![contactus lighthouse](https://user-images.githubusercontent.com/120515252/211732530-12957e03-db47-479b-89f7-813bd7404bda.jpg)


Our Story: Accessibilty, 100.

![ourstory lighthouse](https://user-images.githubusercontent.com/120515252/211732560-31d6ec1b-afbf-46b7-90ab-63333fb21e12.jpg)


Book Table: Accessbility, 100.

![lighthouse book table](https://user-images.githubusercontent.com/120515252/211732574-b0946f8f-70ac-4335-9409-e0335612f423.jpg)


Content

Media:

All written html is my own. All images except for the headers image, are images I have photogrpahed myself.
Header image credit : https://www.pexels.com/photo/rock-in-between-grass-and-flower-368260/

Help:

I use the website https://www.w3schools.com/ to research and discover.

I have not anybody elses code.

Deployment:

I deployed the site using github. 

First I went to settings, then to pages, thereafter scroll to branch, and save to the main branch.
And then its deployed.

Below is the live link to my website:

https://hnjw-png.github.io/restaurante.el.wueon/

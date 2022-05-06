---
layout: essay
type: essay
title: E6 Assignment 3 Checkpoint
date: 2022-05-05
labels:
- Assignment 3

---

<b>Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype</b>
<br>
Screencast: https://www.youtube.com/watch?v=WIoq5IAnEAU
<br>
<b>Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.</b>
<br>
The cart is accessible at anytime while in the products_display page. The button for the cart is in the navbar on the top right of the screen right next to Login. The user is able to move between products pages and add products to their cart, then at any time, the user can click the cart link on the top right where their cart is displayed on its own page and it can be edited by the remove icon to the right of each product. The cart also includes a favorites button for each product, if the user favorites the product on the products_display page then it will show in the cart as well. The user can also choose to go back to the store by clicking a the button 'return to the shop'. When the user is ready to purchase, they click the purchase button in the cart, then they are directed to the invoice page and an email is sent with their purchased products.
<br>
<b>Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.</b>
<br>
Sessions will be used to store user selected products in the cart, if there is no cart, the cart object is created. When the user selects a few products and adds them to the cart, the products are stored in a JSON object with different categories of products in arrays which then can be parsed and loaded by using the loadJSON('get_cart') function. 
<br>
<b>How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</b>
<br>
The user must be logged in to purchase, when the user views the site they are capable of adding things to the cart but only when they are ready to purchase, they must be logged in. I can do this by using sessions to identify who the user is when they log in and if they have not logged in then they will be directed to the login page when selecting purchase.
<br>
<b>Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)</b>
<br>
The localStorage provides a way to store favorites for the user, when they log onto the site they will be able to view the products they previously favorited. The favorites will only be viewable by the user who selected it.
<br>
<b>If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?</b>
<br>
I am doing the project by myself, I have been meeting with the professor and have made significant progress, however, I have a few more things to do until it's finalized.
<br>
<b>How are you approaching Assignment 3 differently than Assignment 2?</b>
<br>
Assignment 3 is much different, I have changed a lot of my code to better suite the requirements. I want to make a fully functional website where multiple users can access and shop. I built on the code from Assignment 2 becuase it provided many necessary components but I have shifted many things around to create a more comprehensive and user friendly website.
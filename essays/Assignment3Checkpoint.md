---
layout: essay
type: essay
title: "Assignment 3 Checkpoint"
# All dates must be YYYY-MM-DD format!
date: 2022-09-28
published: true
labels:
  - Assignment 3 Checkpoint
---
Show what each page will look like. The pages do not have to be “functional” but the design should clear. 
You can view my overview of my website [here](https://youtu.be/bA-ibeSYx_4).
Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.
The site's shopping cart will be a separate page that the user will be able to view or edit. It will also have the capability to add favorite items to the checkout that were previously favorited on the product pages. 
Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.
The items that were entered on the product page will be saved to the user’s quantity array session so that if they log out and then log back in, their shopping cart will be saved. You will be able to access the shopping cart by clicking on the shopping cart button on the product pages. I will organize the quantities entered in the session array by product type. Example: {Jerseys: [0,1,2,0,0,0] Bikes: [1,0,0,0,0,0] Helmets: [1,0,3,4,0,0]}.  Once the shopping cart is loaded, then the desired products will be loaded from the quantity array session. If you have not been previously logged in, then the shopping cart icon will direct you to the login page where you will be able to either register or login. Once you login, the shopping cart will become accessible and you will be able to view or edit your items. 
How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?
I will use the server to check for existing cookies for the specific user and if the user has previously logged in or registered, then they will be able to proceed to the checkout page. If the cookies return that the user was not previously logged in, then it will redirect the user to the login page. Security concerns are that cookies are able to be manipulated and may give unauthorized users who gain access to a users device access to their account while the cookie is still active. To combat this, I will be setting cookies to have a maxAge of 5 minutes so that the user will be logged out after the timer has expired. 
Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)
I will use an onload event to update the invoice with the user’s name and other information as well as the amount of times the user has logged in and the last time the user has logged in by pulling this information from the query string. The onload event will contain if statements to display the information on the invoice page or on the product pages after the user has logged in. For example:
      if(params.has("email")){
        document.getElementById("email").innerHTML = "<b>Email: </b>" + params.get('email');
        console.log(params.get('email'));
This will change the innerHTML of the email span to display the user's info. 
If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?
I will not be working with a partner for Assignment 3.
How are you approaching Assignment 3 differently than Assignment 2?
Firstly, I did not plan out my website like how we did for assignment 3, so mapping it out visually before coding is already a different approach from assignment 2. Secondly, my understanding of coding has improved since I started Assignment 2, so I have a better plan in mind on how and where I will implement the requirements for Assignment 3. I will also tackle each requirement piece by piece in a sequential order so that I will not run into problems later with other requirements which would require me to revise and edit previously completed requirements. Also since cookies and sessions will be used for this assignment, I will change my strategy on how to load user’s saved info from relying heavily on passing info from page to page with the query string to using sessions. 

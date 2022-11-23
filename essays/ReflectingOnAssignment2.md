---
layout: essay
type: essay
title: "Reflecting On Assignment 2 Technical Essay"
# All dates must be YYYY-MM-DD format!
date: 2022-11-22
published: true
labels:
  - Reflecting On Assignment 2 Technical Essay 
---

<b>1. Provide a brief introduction to the assignment along with a link to this page for further details</b> 
<br>
For Assignment 2 we had to create a login, register page, and update the user page. We had to implement these changes onto our Assignment 1 we created. We could either be partners or do it on our own.  We had to ensure that the query string of quantities that was input by the client can get passed over from each page all the way through to the invoice. We also had to personalize the store to whichever user is login in on the site. We also had to use validation on the server side for the client’s username, password, and email. We had to ensure that our site was secure and that all of our validation and client information was being stored on the server side. 
<br>
<b>2. What did you learn from this assignment?</b> 
<br>
Things I learned from this assignment was how to debug proficiently. I was able to understand where to place debugging statements so that I could pinpoint where the issue was coming from. I was also able to utilize functions and if statements much more fluently which greatly helped me to understand where to implement code.
<br>
<b>3. Did you work with a partner? Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself).</b> 
<br>
Yes, I worked with Erin Tachino for Assignment 2.  I believe that we distributed the work fairly equally in the sense that we both had separate tasks to do at all times. We were able to complete most of our work individually or collaborate with each other if we encountered issues. I believe that I did slightly more work only due to the fact that she wasn’t able to complete her Assignment 1 IR by herself but I was able to complete it. We were both able to complete our individual requirements on our own with only minor need for collaboration. With this in mind, I believe that an accurate estimate would be that I contributed 55% and she contributed 45%. Though these percentages reflect the contributions to the actual work done on the project, I wouldn’t say that she was lacking effort as she was able to contribute more in other ways, as in getting in contact with the Professor or Zenan (TA) to get help in arrears where we were stuck. So overall, I would say that our contributions were about even. 
<br>
<b>4. How did you get help when you needed it? What did you need help with? </b> 
<br>
My partner primarily reached out to the Professor and the TA for help. We also utilize additional resources that we found online to help us. We had an issue with the invoice not loading after registering a new user and entering that user’s information into the login page. At least one of us attended every available tutoring session, asked the professor in class for help, or emailed the professor, but the only advice he gave us was to console.log it and try the alternative debugging techniques that we were taught in class. We used all of these techniques and our code looked correct as all the information was being pulled correctly. This one issue cost us days of unnecessary code changes and debugging as the issue didn’t involve our code, but rather nodemon itself. Apparently when we attempted to create a new user, nodemon would register this as a change and would cause the server to restart. Using Node solved this issue as it doesn’t cause the server to restart due to changes being made. We encountered this issue on the first day that we began working on Assignment 2 and wasn't able to get it figured out until a couple hours before the assignment’s due date when the professor finally tried to help us debug it himself. This issue didn’t allow us to move on with the rest of our code as loading the login page and invoice page was very important for ensuring that the query string was correctly being passed from page to page. I also wasn’t able to get started on my IR4 which required that after the log in, I track the users information and display it as well as the amount of times the user logged in.
<br>
<b>5. How was developing this assignment different than assignment #1? </b> 
<br>
The way we developed Assignment 1 was different from Assignment 2 because on Assignment 2 we had to work with the server more. We had to create more validation on the server than on Assignment 1. We also had to make the site more personalized where in Assignment 1 we didn’t have anything on the client who was accessing the website. We also created a lot more if statements for the validation on the server side for Assignment 2. We also had to ensure that for Assignment 2 that the security was stronger than Assignment 1. We did not want the client to be able to access any information from the browser. We also had to create a logout option for our client that was currently logged. 
<br>
<b>6. Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging</b> 
<br>
I believe that we spent 15% on thinking about how to do something, this counts for research as well. Then about 25% writing the code, we spent this time brainstorming about what we want our if statements to valid and functions we wanted to use. Lastly, I would say we spent about 60% of our time testing and debugging. 
<br>
<b> Describe what worked well with this project? What did not work well?</b> 
<br>
I think that our debugging skills and overall thought process worked well for this project as we were able to figure out what we needed to do and where we needed to implement it in our code. I believe that the primary thing that hindered our performance was the issue that we had addressed earlier. Our time spent collaborating was always very productive though, and though we couldn’t figure out what was wrong with the code, the debugging allowed us to be confident that our code was inputted correctly. 
<br>
<b>7. If you could go back in time and do things differently, what would you do differently?</b> 
<br>
I’m not entirely sure what we would have done differently as the only issue we encountered was quite unusual and we wouldn’t have necessarily been able to figure it out on our own. We tried getting in contact with the professor for help as much as we could, so I don’t believe that we could’ve done anything differently except for experimenting with using node earlier on our own. 


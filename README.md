<h1>
  WPI Course Modifier
</h1>
https://jharnois4512-a3-persistence.glitch.me
** Note - You will have to hit the submit button once to get all of the entries in the db to reset to the screen. Only displays defaults on load.
Requirements: 

* Middlewares:
  1. Morgan
  2. Passport
  3. Cookie-session
  4. Connect-timeout
  5. Cookie-parser

* Used the Bootstrap CSS framework

* Used lowdb for persistant data storage

<h3>
  My App  
</h3>

<p>
  The goal of this app is to be able to allow a user, once verified with their github, to be able to modify class information that is stored on the server side of my webApp.
  There were a lot of challenges.  I made my last website in basic HTTP routing.  Changing it over to express posed many challenged, especially for my image for some reason. 
  Other challeges included the routing for my oAuth for Github.  One of the TAs and I tried for 2 hours to get the routing to work correctly.  It was extremely difficult.
  The other major challenge, I thought, was trying to come up with 4 other middleware to use.  I struggled to get them to work.  I reailzed some of them I would have to integrate
  into my project earlier on.  It was something I should have thought about before the end.  I chose to go with the Github strategy of logging in.  I have already implemented an
  MD5 hash login back when I took softEng in D term and I felt like oAuth would be more benificial for me to learn. I used the bootstrap css framework last project so I kept it
  for this one as well.  The only major change I had were the text boxes.  I had to increase their width in order to view the entire placeholder of the text box. I used lowDB for
  this project due to the fact that I use Mongo in my front end job now.  I wanted to explore and use something different.  Not to mention the professor recommended it in class.
  My middleware I listed above.  Morgan allows me to see a detailed "get" request of my website.  Passport is the library I used for authentication.  Cookie session allowed for 
  the storing of session data about the client.  Connect-timeout allows the website to not sit forever attempting to connect, if it can't connect it will timeout and send a move 
  on message (usually to the default timeout page).  Cookie-parser then allows me to be able to log the specific cookies to show the different users and sessions open that I 
  am logging on my DB. Some of my achievements involve middleware, however, I believe there is a bit of a twist on them for reasons why I go above and beyond the simple 
  use of them in my program.
  
</p>

  
<h2>Technical Achievements</h2>
  
Tech Achievement 1: I used OAuth authentication via the GitHub strategy
  
  
Tech Achievement 2: Used cookie-parser to log each cookie to keep track of the different amount of sessions on my website.


Tech Achievement 3: Used Morgan middleware to keep track of the web browser.  I am big into cyber security and seeing what browsers that access my website are important to me.


Tech Achievement 4: Changing background (login page) from the best building on campus to my fraternity.

  
<h3>Design/Evaluation Achievements</h3>
  
  
Design Achievement 1: Logged the username whenever they modified, added, or deleted a class
  
  
Design Achievement 2: Used 3js to render a 3d cube, made it follow the mouse around. Not too close because the background interfeared with clicking the sign-in
  
  
Design Achievement 3: Log the number of views to my main site using the cookie sessions.  This represents allowing me to track the most commonly seen page if I had a larger website


Design Achievement 4: Modified my files to make them more structured.  More like a real software engineering project with structed folders.


Design Achievement 5: Made my background transparent for the threejs object by added in "alpha:true"




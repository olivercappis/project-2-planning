# project-2-planning

Application
├── config
│ ├── connection.js
├──controllers
│ ├── api
│ │ ├── *various routes*
│ ├── index.js
│ ├── homeroute.js
├── db
│ ├── schema.sql
├── models
│ ├── *models for each entity*
├── public
│ ├── css
│ │ ├── *various stylesheets*
│ ├── js
│ │ ├── *frontend javascript*
├── utils
│ ├── *various helpers/middleware*
├── views
│ ├── layouts
│ | ├── main.handlebars
│ ├── not_logged.handlebars
│ ├── login.handlebars
│ ├── signup.handlebars
│ ├── about_you.handlebars
│ ├── selection.handlebars
│ ├── guys.handlebars
│ ├── girls.handlebars
├── server.js


## User Story
As a user I want a fully functional dating website with my user info, log in info and other user date saved and accessed from a databse and so that i can interact and communicate wwith other userson the website

## Acceptance Criteria
GIVEN I open the application 
THEN I am prompted to either sign up or sign in
WHEN I click sign up 
THEN I am met with a form for an email and password
WHEN I enter this information 
THEN I am met with a form to fill in with my personal info
WHEN I click home on the header then I am taken back to the sign up or sign in page
THEN I click sign in 
WHEN I enter my log in information 
THEN I am asked to choose between male and female users 
WHEN I make a selection 
THEN I am shown a list of profiles I am able to interact with
WHEN i push the send email or "like" button
THEN I am able to type a message for the user and send it.





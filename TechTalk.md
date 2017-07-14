
#Project name:
  TechTalk (Aka stack overflow kind with additional features and internal to employees)

#Objective:
  Application for logging technical questions and seeking help from other employees in the company.

##Main functions:
•	Forum to ask questions and seek help
•	Search all the questions logged in the past
•	Tracking and Rewarding top contributors
•	Enabling functionality for setting up mentor groups as an additional feature
•	List responses from Stack overflow website in addition to internal employee responses on search of questions

#Requirements:
  Signup process
  Login process
  Ask a question
  Respond to a question
  Mark the question as resolved
  Store in DB and track who has resolved
  Search existing questions
  Additional features to setup mentor-mentee groups. When mentee asks questions, Mentors will be notified.
  Show contributions and leaderboard information
  Track top 5 contributors in a month, quarter, year and reward them

##Product backlog:
Login related
 		As an unregistered user, I want to register to the site
 		As a registered user I should be able to successfully connect
 		As a registered user I should be able to logout
Main Page related
 		As a registered user I should be able to view the main page after logging in
 		As a registered user I should be able to see the open questions in the most recent order
    As a registered user I should be able to click on any open question and look into more details about the question
    As a registered user I should be able to see and click “Ask Question” option on my main page
 		As a registered user I should be to see search option on main page
    As a registered user I should be able to see leaderboard
Search related
 		As a registered user I should be able to search for tags or ask questions on main page
    As a registered user I should be able to go to search page from main page and search for tags or ask questions
Post related
    As a registered user I should be able to add title in title input box
    As a registered user I should be able to add question details in Description box
    As a registered user I should be able to add tags to my question
Reply related
 		As a registered user I should be able to respond to any of the open questions
Closure related
    As a registered user (questioner) I should be able to acknowledge if the suggested responses has answered my question by accepting it by clicking a check box
    As a registered user I should be able to see once acknowledged the question is closed
    As a registered user I should be able to see on closure the question moved out of the open questions list
Rewards related
    As an application I should be able to track acknowledgements by the registered users and update the score in database for the responder
    As an application I should be able to update leaderboard table with top 5 responders
Stack overflow related
    As a user I should be able to see the stack overflow responses in addition to employee responses
    As a user I should be able to distinguish between employee responses and stack overflow responses

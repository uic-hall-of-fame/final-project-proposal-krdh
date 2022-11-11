# final-project-proposal-krdh
final-project-proposal-krdh created by GitHub Classroom

Our final project for CS 484 will be a web extension of the DylFyt gym log app on the app store which will be a buddy workout feature. Users will log into their DylFyt account (with Firebase Auth API) where they will be asked about their weight class upon first login. Then there will be a list of different movements like bench press, squats, deadlift etc. where the user can join a queue where they will be paired with someone in their weight class. Users will agree on a weight where they will compete by pushing/pulling as much weight as possible over 4 sets. Users will be prompted to log their data by taking turns and once the 4 sets are complete one of the users will be announced as the winner. 

We’ll be using GitHub Pages to host our site and Firebase to host a live database. In Firebase we will create a collection called “Matches” where all match data will live and be linked to each user’s UID. Once a match is over, that data will be deleted. 

For the front end of the web app we’ll be using React/HTML and JS/Node for the backend. Users will log their data on the iOS app which will use some refactored Swift code to send data to the database which will be updated live on the web app. 

For APIs, we’ll be using Firebase Auth and Firebase Realtime Database along with any UI APIs if necessary.

<img width="863" alt="Screen Shot 2022-11-07 at 4 10 28 PM" src="https://user-images.githubusercontent.com/89808902/200426235-5b7151b6-741d-4a22-bb23-90fb3faca249.png">

MVP for November 18th
Users will login and be able to join a Bench Press queue regardless of their weight class. They will take turns logging data for 135 lbs where a winner will be announced at the end.

https://ckclassrooms.github.io/final-project-proposal-krdh/

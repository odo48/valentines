# Be My Valentine 🌹   


### Intro 🎤 ###

A simple web project with a clean UI... For that special someone on valentine's day 😉.  

Happy Valentine's Day 2021 💘.
### Project 👨🏿‍💻 ###

Using Firebase and Cloud Firestore database, this project allows you to interactively ask the user to be your Valentine.  
I've left some console logs in my code, to show all data being retrieved from (and sent to) Cloud Firestore and any errors.  
Note: as this is just a basic project, I didn't implement any authentication / security logic.

Data stored in Cloud Firestore database:
- User's answer from a button click (yes/no)
- User's timestamp at the time of answer
- User's public IP

Made with ❤ using:  
- [JavaScript (ES6+)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)  
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)  
- [SCSS](https://sass-lang.com/documentation/syntax)  
- [Bootstrap 4](https://getbootstrap.com/docs/4.0/getting-started/introduction/)  
- [Animate.css](https://animate.style/)  
- [w3.css](https://www.w3schools.com/w3css/defaulT.asp)  
- [Firebase](https://firebase.google.com/)  
- [Cloud Firestore](https://firebase.google.com/docs/firestore)  
- [ipify API](https://www.ipify.org/)  

### Prerequisites ✅ ###
1. You'll need a Firebase account
    - Create or use existing project
    - Make sure Cloud Firestore database is enabled

### Guide 📃 ###
1. Complete the Prerequisites
1. In **settings.js**:
    - Add your Firebase config, make sure the object name is **firebaseConfig**. Here's an example:  
        ```
        const firebaseConfig = {
            apiKey: "AIzaSyDOCAbC123dEf456GhI789jKl01-MnO",
            authDomain: "myapp-project-123.firebaseapp.com",
            databaseURL: "https://myapp-project-123.firebaseio.com",
            projectId: "myapp-project-123",
            storageBucket: "myapp-project-123.appspot.com",
            messagingSenderId: "65211879809",
            appId: "1:65211879909:web:3ae38ef1cdcb2e01fe5f0c",
            measurementId: "G-8GSGZQ44ST"
        };
        ```
    - Fill in your values for **firestore** and **uiData** objects

### License 📜 ###
- MIT

### Acknowledgments 👏 ###
- [Caitlin Haaf](https://codepen.io/caitlinhaaf/pen/KKpgpqX) - Original SVG and animation for the bee

### People 👥 ###
| Name                	|  Title              	|  Authority Level      | Website                  	|
|-------------------	| -------------------	| -------------------	|--------------------------	|
| Teodor Dacu	|  Author +        	    |  Admin +        	    | |

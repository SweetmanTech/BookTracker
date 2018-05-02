# Book Tracker
Book Tracking App using Firebase Backend  
Live - http://patricksweetman.com/books/index.html

## Guide
Part I -https://youtu.be/moGcZHjq21Y  
Part II - https://youtu.be/XZlP6fqvGNg  

## Platforms
* Web

## Getting Started
1. Clone Repo
```
git clone https://github.com/SweetmanTech/BookTracker.git
```
2. Change Directory to Project
```
cd BookTracker
```
3. Update Firebase Config in BookTracker/add/index.html
```
//Change this block with your code
// Initialize Firebase
var config = {
  apiKey: {API-KEY},
  authDomain: {DOMAIN},
  databaseURL: {DATABASE-URL},
  projectId: {PROJECT-ID},
};
firebase.initializeApp(config);
```

4. Deploy and Run
you may need to add the deployed website in your Firebase console  (Auth -> Sign-In Method -> Authorized Domains) to clear any initial errors

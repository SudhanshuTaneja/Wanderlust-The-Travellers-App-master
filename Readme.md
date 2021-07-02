#  Wanderlust - The Traveller's App

## Project Description
Wanderlust is an **Android app** that allows its users to keep track of their journey experiences by allowing them to save their journeys in the form of a trip diary and have all their travel experiences saved at one place. Its more of a **Check-in** application. In order to spice things up, we gave this app a **social platform** feel by allowing the user to add friends and share his profile containing journeys count and friends count with each other. 

## Tools and APIs Used
* Android Studio is used to develop the whole android application in Java
* Google Maps API
* Facebook and Twitter SDKs (for fetching and uploading data on these platforms)
* Google Places API
* Firebase Authentication
* Cloud Messaging using Google Firebase
* Firebase Storage 
* Firebase Analytics including Crashlytics, Performance Monitoring
* Google Admob APIs
* Firebase Realtime Database


## Functionalities

Wanderlust uses **Firebase Phone Number Authentication** which verifies a user’s phone number by sending a code to it. The user is then authenticated to use the app.

Our app also has a **Journeys Map** which has journeys as labels placed on locations which have been visited.

The app incorporates a **Step Count** feature which allows the travellers to count the number of steps they took while being on a journey. It also incorporates a **Compass using Magnetic Sensors** which proves helpful for travellers while travelling.

In order to make the app usable for a wide range of audiences, our app supports **language support in Urdu**. We have also added **Text-to-Speech** feature by reading the journey title and description for users with some disabilities. Moreover, our app can also be used using **Voice Commands**. The user speaks the command and our app recognizes the command e.g Exit App will close the app. 

Wanderlust seamlessly incorporates **Social Media Integration using Facebook and Twitter APIs**. This allows users to share their journey experiences on these social platforms. 

Moreover, the app also incorporates **Google Admob** with customized ads for targeting travellers. We have also integrated **Firebase Analytics** which allows us to have deeper insights into how a user uses our apps so that we can use those insights and improve our app.

Wanderlust was designed with **major focus on HCI**. It incorporates **Ben Shneiderman’s 'Golden Rules of Interface Design'** including

* Consistency
* Design Dialogs to Yield Closure
* Offer Informative Feedback
* Prevention of Errors
* Keep Users in Control
* Reduce Cognitive Load
* Universal Usability

Moreover the **modern UI/UX guidelines for Android App Design** have been followed including:

* Visibility (making features visible to user, used Bottom Navigation Bar)
* Splash Screens
* Audio Feedback using Text to Speech
* Enhanced Accessibility Using Google Maps

## How to Run

An apk file named Wanderlust.apk is provided which can be installed on an Android Phone. 

In order to have a look at the code files and understand the working, simply download this repository and open Android Studio and browse to the downloaded project and open it. It will load the project files and the code will be ready to run. Before running the app, use your Google Account to register this Application on Firebase Console, with any name you want. Then using that Google Account, login to Android Studio. Then you can run the project. If you face any issues with the Firebase Database, you can ping me up.                      

Emergency Help Website
This project is an emergency contact website, designed for quick access to family members' contact information in case of an accident. The website works by scanning a QR code and helping bystanders quickly contact the right people based on who needs help.

Features
Profile Selection: Choose who needs help (three different people who share the bike).
Responsive Design: The site is mobile-friendly for easy use on smartphones.
Dynamic Contact Info: Depending on who you select, the website displays different family members' contact numbers and the person's blood group.
Google Maps Redirection: The Comet Busters address is linked to Google Maps for easy navigation.
Getting Started
Prerequisites
Make sure you have Node.js and npm installed on your machine.

Installation
Clone the project repository.

Navigate to the project folder in your terminal:

bash
Copy code
cd /path/to/project
Install the dependencies:

bash
Copy code
npm install
Running the App
To run the app locally in development mode:

bash
Copy code
npm start
This will open the app in your browser at http://localhost:3000.

Building for Production
To build a production version of the app, run:

bash
Copy code
npm run build
The app will be optimized and ready to be deployed from the build folder.

Deploying
The build folder contains all the files you need to deploy to a static hosting service like GitHub Pages, Netlify, or Firebase Hosting.

How It Works
When the website is accessed, the user is asked, "Who is in need of help?"
The user selects one of three profiles (those who share the bike) by clicking their picture.
The website displays the contact numbers of the selected person's family members and their blood group.
The Comet Busters address includes a link that opens Google Maps for directions.
Available Scripts
In the project directory, you can run:

npm start: Runs the app in development mode at http://localhost:3000.
npm run build: Builds the app for production.
npm run eject: Removes the abstraction provided by Create React App to give you full control over configuration.

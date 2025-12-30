# DevToolkit

A modular web application designed to support students and beginner developers by centralizing development tools, learning resources, and career preparation features. Built as a final group project for CSC 4110 Software Engineering at Wayne State University.

## Overview
DevToolkit addresses the problem of fragmented beginner resources by offering a single platform for tool discovery, guided learning, and early career preparation. The project demonstrates modular front end architecture and lightweight backend integration using Firebase services.

## Key Features
- Multi page responsive web application  
- Centralized developer tool browsing and comparison  
- Learning and career preparation modules  
- Firebase Authentication for user accounts  
- User specific favorites and saved data  
- Contact and suggestion forms with validation  
- Graceful fallback behavior for signed out users  

## Technologies Used
- HTML5  
- CSS3  
- Bootstrap  
- JavaScript ES6  
- Firebase Authentication  
- Firebase Firestore  
- GitHub Pages  

## Backend Architecture
Firebase Authentication manages user registration, login, logout, and session persistence. Firestore stores user scoped data including favorites, contacts, and suggestions. Security rules ensure users can only access their own data.

## Project Structure
DevToolkit/
├── html pages
├── css/
│ └── style.css
├── js/
│ └── modular feature scripts
├── data/
│ └── tools.json
└── images/

## How to Run Locally
Open index.html in a modern web browser.  
For development, Visual Studio Code with Live Server is recommended.

## Course Information
CSC 4110 Software Engineering  
Wayne State University  

## Future Improvements
- User analytics dashboard  
- Role based access control  
- Expanded learning pathways  

GameMeet

GameMeet is a web platform that allows users to find others to play live or remote sessions of board games, card games, or role-playing games (like Dungeons & Dragons).

Currently, the project consists of three main pages: Home/Index, Create Session, and Profile.

Home Page

The Home page allows users to search and filter sessions by location, type of game, or date.

The project includes 6 hardcoded dummy sessions to make the platform appear active.

Users can join these sessions, and joined sessions will appear on their Profile page.

An AI-powered chatbot (using OpenAI) is fully functional and available on this page.

Create Session Page

The Create Session page lets users create their own game sessions.

Ideally, the Game Name field would be integrated with the Board Game Geek XML API, which contains a database of hundreds of thousands of board games with detailed information.

Since the API requires a paid key, the project uses a local database of 20 games (found in script.js) to simulate the integration.

Users can create custom sessions, which will then appear on the Home page. These custom sessions can be deleted.

Profile Page

The Profile page simulates a user profile (without a login/register flow).

Users can add information they want to share.

The page displays all sessions the user has either created or joined.

Technologies Used

HTML5 and CSS3 for structure and styling

JavaScript (ES6+) for interactivity and API integration

OpenAI API for the AI-powered chatbot

Git for version control

Project Notes

The website is fully responsive across devices.

Client-side validation is implemented for forms.

Accessibility and web standards were considered in the design.

API calls include proper error handling and user feedback.

Getting Started

Follow these instructions to set up and run the project locally.

Prerequisites

Git
 installed

Node.js
 (optional, only needed if you plan to extend the project with a server or build tools)

Installation

Clone the repository

git clone https://github.com/your-username/GameMeet.git


Navigate into the project directory

cd GameMeet


Open the project in your code editor

code .


(Replace code . with your editor’s command if not using VS Code)

Open index.html in your browser

You can double-click the file or use a live server extension for real-time updates.

Working with Git

Check the status

git status


Stage files for commit

git add .


Commit your changes

git commit -m "Initial project setup with all pages"


Push to GitHub

git branch -M main
git remote add origin https://github.com/your-username/GameMeet.git
git push -u origin main

Notes on AI Integration

The AI chatbot uses the OpenAI API.

Replace your API key in script.js for full functionality.

Proper error handling is implemented to avoid breaking the UI if the API fails.
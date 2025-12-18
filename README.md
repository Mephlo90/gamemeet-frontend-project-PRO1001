##GameMeet – PRO1001 Frontend Essentials
----------------------------------------
Project Description
-------------------
GameMeet is a frontend web platform designed to help users find and organize live or remote game sessions for board games, card games, and role-playing games such as Dungeons & Dragons.

The main goal of the project is to explore how a user-friendly interface can support people who want to connect with others around shared gaming interests, without relying on a backend or authentication system.

The project currently consists of three main pages:

--
##Home / Index
--
- Displays available game sessions.

- Includes search and filter functionality by location, game type, and date.

- Contains six hardcoded dummy sessions to simulate an active platform.

- Users can join sessions, which are then reflected on the Profile page.

- Includes an AI-powered chatbot (using the OpenAI API) that assists users with questions and suggestions.

--
##Create Session
--
- Allows users to create their own game sessions.

- The Game Name field is designed to work with the BoardGameGeek XML API.

- Since this API requires a paid key, a local database of 20 games (stored in script.js) is used to simulate this integration.

- User-created sessions appear on the Home page and can be deleted.

--
##Profile
--
- Simulates a user profile without a login or registration flow.

- Users can add personal information they wish to share.

- Displays sessions the user has created or joined.

The project is intended as a functional prototype rather than a fully deployed product.

----------------------
##Setup & Installation
----------------------

No complex setup is required to run this project locally.

If you want to use the AI chatbot:

-You will need an OpenAI API key.

-Replace the placeholder API key inside script.js with your own key.

-Basic error handling is implemented so the UI does not break if the API fails.

-No backend, database, or build tools are required.

--------------------
##How to Run Locally
--------------------

Clone the repository:

- git clone https://github.com/your-username/GameMeet.git


Navigate into the project folder:

- cd GameMeet


Open the project in your code editor:

- code .


(Replace code . with your editor’s command if needed.)

Open index.html in your browser:

- Double-click the file

Or use a Live Server extension for easier development

-------------------
##Known Limitations
-------------------

There is no backend or database; all data is stored locally using localStorage.

There is no authentication or user account system.

Dummy sessions on the Home page are hardcoded and cannot be deleted.

The BoardGameGeek API integration is simulated using a local dataset.

The AI chatbot depends on internet access and a valid OpenAI API key.

This project is a prototype and not intended for production use.

---------------------
##Future Improvements
---------------------
Given more time and resources, the following improvements could be explored:

- Implementing a real login and registration flow.

- Adding a backend and database for persistent user data and sessions.

- Fully integrating the BoardGameGeek API.

- Improving matchmaking features (recommendations based on preferences).

- Expanding accessibility testing with real users.

- Enhancing AI features with clearer transparency and user controls.

--
##Technologies Used
--
HTML5 and CSS3 for structure and styling

JavaScript (ES6+) for interactivity and logic

OpenAI API for the AI-powered chatbot

Git & GitHub for version control

--
##Notes on AI Integration
--
The chatbot uses the OpenAI API to provide user assistance.

API calls include error handling and fallback messaging.

AI output is treated as guidance, not authoritative information.

Ethical considerations such as transparency and user trust were taken into account.

AI Assistance Disclosure

This project was developed with the assistance of AI tools (ChatGPT) for:

-Code suggestions and refactoring

-UI/UX ideas

-Debugging support

-Documentation drafting

All generated code and content were reviewed, adapted, and integrated manually.
Final implementation decisions, feature selection, and architectural choices were made by the author.

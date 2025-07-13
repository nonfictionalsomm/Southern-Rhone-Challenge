The Southern Rhône: A Wine Master's Challenge
1. Overview
This project is a comprehensive, data-driven, single-file HTML web application designed as an interactive study game for advanced wine students. Titled "The Southern Rhône: A Wine Master's Challenge," it provides a series of quizzes and study tools based on an in-depth research document covering the history, terroir, grapes, laws, gastronomy, and market context of the Southern Rhône wine region.

The application is built to be entirely self-contained, requiring only a modern web browser to run.

2. Features
The game is structured around a central main menu that provides access to seven distinct study modules.

Core Quiz Modules (Multiple Choice & Timeline)
The Historian's Scroll: A five-question timeline challenge where the player must correctly order key historical events.

The Terroir Architect: A 10-question multiple-choice quiz on the geology, geography, and climate of the region.

The Ampelographer's Challenge: A 10-question multiple-choice quiz focused on the key grape varieties.

The Lawmaker's Desk: A 10-question multiple-choice quiz covering the complexities of AOC law and winemaking regulations.

The Gastronome's Table: A 10-question multiple-choice quiz on the region's classic cuisine, ingredients, and food pairings.

The Critic's Corner: A 10-question multiple-choice quiz about iconic producers, vintages, and market context.

Study & AI Features
Flashcard Study: A powerful study tool that allows the user to build a custom deck of flashcards from any combination of the core topics. For historical events, individual flashcards are created for each event and its corresponding date, providing a more effective study experience.

AI-Powered Insights (Gemini API):

Ampelography Profile: After correctly answering a question about a grape in "The Ampelographer's Challenge," the user can generate a detailed, textbook-style profile of that variety.

Professional Tasting Note: After correctly answering a question about an iconic wine in "The Critic's Corner," the user can generate a professional-style tasting note.

Gastronomic Explanation: After correctly answering a question about a food pairing in "The Gastronome's Table," the user can generate a detailed explanation of the gastronomic principles behind the pairing.

User Interface
Responsive Design: The application is fully responsive and mobile-first, ensuring a seamless experience on desktops, tablets, and phones.

Modal System: The game uses a system of modals to provide a welcome message, instructions for each module, and end-of-game score reports.

AI Settings: A dedicated settings modal allows the user to input and save their Google AI Studio API key to enable the AI-powered features.

3. Setup & Usage
Running the Application
The application is designed for simplicity. As it is a single, self-contained index.html file, no build process or server is required.

Ensure you have the index.html file.

Open the file directly in any modern web browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

Enabling AI Features
The AI-powered content generation relies on the Google Gemini API. To use these features, you must provide your own API key.

Get an API Key: Visit Google AI Studio to generate a free API key.

Open AI Settings: On the main menu of the application, click the "⚙️ AI Settings" button.

Enter Your Key: Paste your API key into the input field in the modal.

Save: Click the "Save and Close" button. Your key will be saved in your browser's local storage for future sessions.

Note: Your API key is treated like a password. It is only stored in your browser and is never transmitted to any server other than the official Google AI API endpoint.

4. Technical Stack
Frontend: Vanilla JavaScript, HTML5

Styling: Tailwind CSS (loaded via CDN)

AI Integration: Google Gemini API (gemini-2.0-flash model)

5. Content Source
All questions, answers, and factual information used to build the game modules are derived exclusively from the provided comprehensive research document: "Southern Rhone Valley Wine Analysis". This ensures that the game is a true and accurate study companion to the source material.

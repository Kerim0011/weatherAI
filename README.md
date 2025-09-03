AI Weather Assistant

This is a single-file web application that provides a simple and interactive chat assistant. It is built to answer general questions and, most importantly, provide real-time weather information by leveraging the power of Google's Gemini AI and its Search Grounding feature.

🚀 Features
Interactive Chat Interface: A clean and simple chat window for a smooth user experience.

Gemini AI Integration: Uses the gemini-2.5-flash-preview-05-20 model to provide intelligent responses.

Real-time Information: The Search Grounding tool allows the AI to fetch up-to-date information, such as current weather conditions for any location.

Conversation History: The chat maintains context by remembering previous messages in the conversation.

Loading Indicator: A "Thinking..." state lets the user know when the AI is processing their request.

Responsive Design: Built with Tailwind CSS for a modern look that works on both desktop and mobile devices.

🛠️ Technologies Used
HTML5: For the application's structure.

CSS: Styled with the Tailwind CSS framework for a clean, modern look.

JavaScript: Powers the chat logic, API calls, and dynamic content.

Google Gemini API: The core AI model that powers the assistant's responses.

🔧 Setup and Usage
This project is a single index.html file, making it incredibly easy to set up and run.

Save the File: Save the provided code as a file named index.html on your computer.

Open in Browser: Double-click the file to open it in your preferred web browser (e.g., Chrome, Firefox, Edge).

API Key Configuration
For the AI assistant to work, you must use a Google Gemini API key.

Get a Key: Visit the Google AI Studio website and create a new API key.

Paste the Key: Open the index.html file in a text editor. Find the following line in the <script> tag:

const apiKey = ""; // Paste your API key here

Replace the empty string with your key and save the file.

After pasting your key, the assistant should be fully functional. Simply type a question into the text box and press Enter or click the Send button.

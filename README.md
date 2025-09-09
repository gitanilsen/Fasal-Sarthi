Fasal-Sarathi AI (फसल सारथी AI)
Tagline: Your Personal AI Farming Expert, from Seed to Market.

Fasal-Sarathi AI is a web-based prototype of a smart farming assistant designed specifically for Indian farmers. It leverages the power of Google's Gemini AI to provide actionable, personalized, and proactive guidance, moving beyond generic information to become a true digital companion. The goal is to help farmers increase yield, reduce costs, and make informed decisions by putting advanced AI tools directly into their hands.

✨ Core Features
This application is packed with features that address the core challenges of modern farming:

🏡 Dynamic Action Plan (DAP): The home screen provides a personalized, daily to-do list based on the farmer's crop, location, and local weather.

📸 AI Camera Diagnosis: Farmers can upload a photo of a plant leaf, and the AI will analyze it to identify diseases, pests, or nutrient deficiencies and suggest remedies.

🤖 AI Agronomist Chatbot: A conversational AI assistant, "Krishi-Gyaan," trained to answer any farming-related question in simple language.

📈 AI Market Intelligence: Provides current market prices and uses AI to predict future price trends for the next harvest season, helping farmers sell at the best time.

🌦️ AI Weather Advisory: The AI analyzes the 5-day weather forecast and generates specific, actionable advice (e.g., "Postpone spraying due to upcoming rain").

📜 Government Scheme Finder: An AI-powered search to help farmers find and understand relevant government schemes and subsidies.

💸 Expense Tracker: A simple tool to log and track all farm-related expenses, providing a clear financial overview of the crop season.

🛠️ Technology Stack
This prototype is built with a focus on accessibility and modern web standards:

Frontend: HTML5, CSS3, modern JavaScript (ES6+)

Styling: Tailwind CSS for a utility-first, mobile-responsive design.

AI Backend: The application is designed to connect to the Google Gemini AI API. For demonstration purposes, this version contains a high-fidelity Embedded AI Engine that simulates the API's responses, allowing the app to run without an API key.

🚀 How to Run
You can run this application directly in any modern web browser.

Download the fasal_sarathi_ai.html file.

Open the file in your browser (e.g., Chrome, Firefox, Safari).

For the best experience, use your browser's developer tools to switch to a mobile view (e.g., iPhone or Android device simulation).

Connecting to the Live AI:

The current version works offline. To connect it to the live Google AI, you would need to:

Obtain a free API key from Google AI Studio.

In the <script> section of the HTML file, replace the placeholder in the API_KEY constant with your actual key.

Use the callGeminiAPI function instead of the callEmbeddedAI function in the app's logic.

💡 Future Scope
Fasal-Sarathi AI is a prototype with immense potential. Future development could include:

Developing native Android and iOS applications.

Integrating real-time satellite imagery for NDVI (crop health) analysis.

Hyper-local soil data integration.

Support for more regional Indian languages and dialects.

Building a community feature for farmers to connect and share knowledge.

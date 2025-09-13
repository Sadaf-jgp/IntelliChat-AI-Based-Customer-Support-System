# IntelliChat-AI-Based-Customer-Support-System
AI Customer Service Chatbot is a web-based assistant that provides 24/7 automated support for queries like order tracking, shipping, and returns. Built with JavaScript, Tailwind CSS, and Compromise NLP, it detects intent, analyzes input, and delivers instant responses through a clean, user-friendly interface.
AI-powered, web-based chatbot for automated 24/7 customer support.

📌 Overview

The AI Customer Service Chatbot is a prototype intelligent assistant designed to handle common customer queries like order tracking, shipping details, and return policies. It is built using JavaScript, Tailwind CSS, and the Compromise NLP library for intent detection. The chatbot provides instant, predefined responses through a clean, user-friendly interface, making customer support more efficient.

🚀 Features

24/7 automated support for queries (orders, returns, shipping, FAQs).

NLP-powered intent detection (via Compromise + custom logic).

Instant responses loaded from a configurable JSON file.

Simple and modular architecture for easy customization.

Lightweight web-based UI styled with Tailwind CSS.

Local development setup with live-server.

🛠️ Tech Stack

Frontend: HTML, JavaScript, Tailwind CSS

NLP: Compromise (intent extraction logic in nlp.js)

nlp

Server/Dev Tooling: Node.js, Live Server

package

📂 Project Structure

index.html → Main UI

css/styles.css → Custom styles

js/chatbot.js → Chatbot logic & DOM updates

js/nlp.js → NLP-based intent detection

nlp

assets/data/responses.json → Predefined chatbot responses

package.json → Node.js config & scripts

package

⚡ Getting Started

Clone the repository:

git clone https://github.com/your-username/customer-service-chatbot.git
cd customer-service-chatbot


Install dependencies:

npm install


Run locally:

npm start


Open http://localhost:8080
 in a browser.

🎯 Future Enhancements

Integration with real order tracking APIs.

Support for multi-language queries.

Rich UI with images, avatars, and chat history persistence.

Deployment on cloud platforms for production.

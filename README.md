💬 Simple FAQ Chatbot (Frontend Only)
A lightweight AI-style FAQ chatbot built with HTML, CSS, and Vanilla JavaScript. Designed for customer support or eCommerce use-cases. This version uses a simple predefined Q&A logic with no server/backend.

🚀 Features
Toggle-based popup chat UI 🟢

Predefined keyword-based responses 💬

Auto-scrolls to latest message 🧭

Works entirely in the browser (no backend) 🖥️


🔧 How It Works
User types a question.

JavaScript checks for keywords (e.g., support, price, thank you).

A relevant answer is returned if a keyword match is found.

If not found, the chatbot replies: "Sorry, I don't understand. Can you try rephrasing?"

🛠️ Tech Stack
HTML5

CSS3

JavaScript (Vanilla)

📁 Project Structure
bash
Copy
Edit
📦 chatbot/
├── index.html      # Main page
├── style.css       # Chatbot styles
└── script.js       # Chatbot logic
📝 Sample Keywords & Responses
js
Copy
Edit
"support|help|contact":
  "Our customer support is available Monday to Saturday, 8AM to 8PM Sri Lanka time. Reach us at support@yourcompany.lk or +94 77 123 4567.",

"thank you|thanks|thx":
  "You're very welcome! 😊 If you have more questions, I'm here to help."
  
💡 Next Steps
✅ Add more Q&A pairs (shipping, returns, account help, etc.)
🔜 Connect to OpenAI API for dynamic answers
🔜 Add Node.js backend for advanced functionality
🔜 Store user queries or chat history

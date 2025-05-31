# 💧 Jal Vaani – Groundwater Awareness Chatbot

**Jal Vaani** is a web-based AI chatbot that spreads awareness about groundwater levels and conservation techniques. It serves as an educational and interactive tool for users to understand local water data, explore conservation tips, and get answers to groundwater-related queries.  

This project was built with a custom NLP model trained on over 6 lakh groundwater records. The chatbot uses a simple and user-friendly React frontend with a Flask backend, integrated with a MongoDB database for storing chat history and user interactions.

---

## 🚀 Features

- 💬 Chatbot interface for groundwater FAQs and suggestions  
- 📊 AI model trained on real groundwater datasets  
- 🌐 React.js frontend with Tailwind CSS and shadcn/ui components  
- ⚙️ Flask API backend using Groq LLaMA3-8B for NLP responses  
- 🗃️ MongoDB integration for user chat history  
- 📍 Future-ready for location-based groundwater data insights  

---

## 🧰 Tech Stack

| Component   | Technology                    |
|-------------|-------------------------------|
| Frontend    | React.js, Tailwind CSS, shadcn/ui |
| Backend     | Flask, Python                  |
| AI Model    | Groq LLaMA3-8B (via API)       |
| Database    | MongoDB                        |
| Dev Tools   | VSCode, Postman, Netlify       |

---

## 📁 Project Structure

jal-vaani/
├── frontend/
│ ├── client/ # React components
│ ├── pages/ # Chat UI and pages
│ ├── shared/ # Shared hooks or utilities
│ └── ...
├── groundwater-chatbot/
│ ├── chatbot.py # NLP chatbot logic
│ ├── config.py # API keys and config
│ ├── llm.txt # Prompt or knowledge base
│ └── ...
├── server/
│ └── app.py # Flask backend server
└── README.md



## 🛠️ How to Run the Project Locally

Follow these steps to run both frontend and backend on your local machine:

### 🔹 Step 1: Clone the Repository
git clone https://github.com/yourusername/jal-vaani.git
cd jal-vaani

cd groundwater-chatbot
python -m venv venv
source venv/bin/activate       # Windows: venv\Scripts\activate
pip install -r requirements.txt
GROQ_API_KEY=your_groq_api_key
python chatbot.py
cd frontend/client
npm install
npm run dev
MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/jalvaani




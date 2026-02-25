# 🚀 LinkedIn Post Generator using AI

An AI-powered LinkedIn Post Generator built using **Python, Streamlit, and Large Language Models (LLMs)** with **few-shot prompting**.  
This application allows users to generate high-quality LinkedIn posts based on topic, length, and language using real example-based prompting.

---

## 📌 Features

- Generate LinkedIn posts using AI
- Few-shot prompting using real LinkedIn post examples
- Interactive Streamlit frontend UI
- Filter posts by:
  - Topic
  - Length (Short, Medium, Long)
  - Language
- Secure API key management using `.env`
- Structured and scalable project architecture
- Production-style AI project design

---

## 🧠 How It Works

1. Preprocessed LinkedIn posts are stored in JSON format
2. Posts are loaded and filtered based on user selection
3. Few-shot examples are added to the prompt
4. LLM generates a new LinkedIn post based on selected criteria
5. Streamlit displays the generated post in the frontend

---

## 🛠️ Tech Stack

| Technology | Purpose |
|----------|---------|
| Python | Core programming language |
| Streamlit | Frontend UI |
| Pandas | Data processing |
| LLM (Groq / OpenAI) | AI text generation |
| JSON | Data storage |
| Git & GitHub | Version control |
| dotenv | Secure API key management |

---


## ⚙️ Installation and Setup

### Step 1: Clone repository

```bash
git clone https://github.com/YOUR_USERNAME/linkedin-post-generator.git
cd linkedin-post-generator
Step 2: Create virtual environment
python -m venv venv

Activate:

Windows:

venv\Scripts\activate

Mac/Linux:

source venv/bin/activate
Step 3: Install dependencies
pip install streamlit pandas python-dotenv langchain groq
Step 4: Setup environment variables

Create .env file:

GROQ_API_KEY=your_api_key_here
Step 5: Run the application
streamlit run main.py
🌐 Application UI

The application allows users to:

Select topic

Select post length

Generate AI-powered LinkedIn post

🔐 Security

API keys are stored securely using .env and are not pushed to GitHub.

📈 Future Improvements

Multiple language support

Export posts to file

Deploy on cloud

Add authentication

Save generated posts history

👨‍💻 Author

Sanjay Kumar S

GitHub: https://github.com/SANJAYKUMAR-05

LinkedIn: https://linkedin.com/
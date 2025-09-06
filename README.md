# FlowFi.ai-PrototypeV1.0

FlowFi.ai - Your Intelligent Expense Manager (Prototype V1.0)
Tired of tedious expense tracking? FlowFi.ai is a smart, voice-first expense manager that uses AI to make logging and understanding your finances effortless. Simply speak your expenses, edit them in a clean interface, and chat with an AI analyst to gain insights into your spending habits.

✨ Core Features
🎙️ Voice-First Input: Uses OpenAI's Whisper to accurately transcribe and categorize expenses from your voice.

✍️ Manual & Editable Entries: Full CRUD (Create, Read, Update, Delete) functionality for your expenses through an interactive table.

📊 Interactive Dashboard: Get a quick overview of your finances with dashboard cards for Total Spend and Average Transaction.

📈 Multiple Visualizations: Understand your spending patterns at a glance with three distinct charts:

Expense Breakdown (Pie Chart)

Spending by Category (Bar Chart)

Spending Over Time (Line Chart)

🚨 Custom Budget Alerts: Set monthly budgets for different categories and receive alerts when you're nearing or have exceeded them.

🤖 AI-Powered Chatbot (RAG): Chat with your data! Our Retrieval-Augmented Generation (RAG) chatbot can answer complex questions, perform calculations, and even show filtered tables of your expenses.

🛠️ Tech Stack
Backend & UI: Python, Gradio

AI & Machine Learning:

ASR: OpenAI Whisper

RAG Pipeline: LangChain

Vector Search: FAISS (Facebook AI Similarity Search)

LLM: Google's Flan-T5-Base

Embeddings: BAAI/bge-base-en-v1.5

Data Visualization: Plotly

Data Handling: Pandas

🚀 Getting Started
This entire application is self-contained in a Google Colab notebook. You can run it with a single click—no local installation required! No API Key required.

How to Run:
Click the "Open in Colab" button above.

In the Colab notebook, click Runn all btn.

Wait for the dependencies to install and the models to load (this can take a few minutes).

A public Gradio link will appear in the output. Click it to open the FlowFi.ai application in your browser!

🗺️ Roadmap (Future Work)
FlowFi.ai is currently a prototype. Here are some planned features for future versions:

[ ] Persistent Database: Replace the temporary JSON file with a cloud database like Firebase or Supabase for permanent storage.

[ ] User Authentication: Allow multiple users to have their own private accounts.

[ ] Enhanced Analytics: Implement automatic trend detection and saving suggestions.

[ ] Mobile-First UI: Further refine the UI for an even better mobile experience using Flutter.

[ ] Add different types of expenses using voice assistent like google, siri, alexa etc.
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
or email tushardebclg2002@gmail.com

📜 License
This project is licensed under the MIT License - see the LICENSE.md file for details.

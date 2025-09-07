
# FlowFi.ai - Intelligent Expense Manager (Prototype V1.0)  
FlowFi.ai is a **smart, voice-first expense manager** that makes tracking and understanding your finances effortless. Log your expenses by speaking, edit them in a clean interface, and chat with an AI analyst to gain insights into your spending habits—all in one tool.  

***

### ✨ Core Features
- 🎙️ **Voice-First Input**: Uses OpenAI Whisper to transcribe and categorize expenses directly from your voice.  
- ✍️ **Manual & Editable Entries**: Full CRUD (Create, Read, Update, Delete) functionality via an interactive expense table.  
- 📊 **Interactive Dashboard**: Quick overview with dashboard cards for *Total Spend* and *Average Transaction*.  
- 📈 **Multiple Visualizations**:  
  - Expense Breakdown (Pie Chart)  
  - Spending by Category (Bar Chart)  
  - Spending Over Time (Line Chart)  
- 🚨 **Custom Budget Alerts**: Set monthly budgets per category and get alerts when nearing or exceeding limits.  
- 🤖 **AI-Powered Chatbot (RAG)**: Chat with your data! Ask questions, perform calculations, and view filtered expense tables.  

***

### 🖼️ Screenshots
 

- <img width="1863" height="850" alt="image" src="https://github.com/user-attachments/assets/edbbfe9c-c419-4a73-ab2a-2cfe56fdeb77" />
 
***

### 🛠️ Tech Stack
- **Backend & UI**: Python, Gradio  
- **AI & Machine Learning**:  
  - ASR: OpenAI Whisper  
  - RAG Pipeline: LangChain  
  - Vector Search: FAISS (Facebook AI Similarity Search)  
  - LLM: Google Flan-T5-Base  
  - Embeddings: `BAAI/bge-base-en-v1.5`  
- **Data Visualization**: Plotly  
- **Data Handling**: Pandas  

***

### 🚀 Getting Started
FlowFi.ai is fully contained within a **Google Colab notebook**. No setup or installation required.  
**Steps to Run:**  
1. Click the **“Open in Colab”** button in the repository.  
2. In Colab, click **Run All**.  
3. Wait for dependencies to install and models to load.  
4. A public **Gradio link** will appear in the output.  
5. Click the link to open FlowFi.ai in your browser and start managing expenses!  

***

### 🗺️ Roadmap
Planned features for future versions:  
- [ ] Persistent Database (e.g., Firebase or Supabase) for permanent data storage.  
- [ ] User Authentication with private accounts.  
- [ ] Enhanced Analytics with auto trend detection and saving suggestions.  
- [ ] Mobile-First UI optimized with Flutter.  
- [ ] Voice Assistant Integrations (Google Assistant, Siri, Alexa).  

***

### 🤝 Contributing
We welcome contributions, issues, and feature requests!  
- Submit issues via the repository’s **Issues** tab.  
- Contact: [tushardebclg2002@gmail.com](mailto:tushardebclg2002@gmail.com)  

***

### 📜 License
This project is licensed under the **MIT License** – see the [LICENSE.md](LICENSE.md) file for details.  

***

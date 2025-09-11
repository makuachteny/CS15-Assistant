# CS.15 Assistant 🎓🤖  
**CS.15 Assistant** is a machine learning–powered chatbot designed during Tufts 2025 spring semester Hackathon to support students CS 15 (Data Structures and Algorithm) by answering questions about class lectures and topics. Instead of giving away direct solutions, the assistant guides learners by providing explanations, context, and helpful insights to reinforce understanding.  

Built using **ChatGPT 3.0** and **Retrieval-Augmented Generation (RAGs)**, the assistant can retrieve relevant lecture materials and combine them with generative AI to produce accurate, context-aware answers.  

---

## ✨ Features  
- 📚 **Lecture-Aware** – Trained on course lectures for subject-specific accuracy  
- 🤝 **Learning Support** – Offers guidance and explanations without revealing complete answers  
- 🔎 **Retrieval-Augmented Generation (RAGs)** – Retrieves relevant lecture content before generating responses  
- 🧠 **ChatGPT 3.0 Integration** – Combines powerful language generation with course-specific knowledge  
- 🎯 **Classroom Focused** – Built to help students understand concepts discussed in class  

## How It Works
```bash
+------------------+         +------------------+         +-------------------+
|   Lecture Data   | ----->  |   Embeddings &   | ----->  |   Vector Database |
| (Class Transcripts)|       | Preprocessing    |         |   (Knowledge Base)|
+------------------+         +------------------+         +-------------------+
                                                                  |
                                                                  v
                                                        +-------------------+
                                                        |   RAG Retrieval   |
                                                        | (Find Relevant    |
                                                        |  Lecture Chunks)  |
                                                        +-------------------+
                                                                  |
                                                                  v
                                                        +-------------------+
                                                        |   ChatGPT 3.0     |
                                                        | (Generate Guided  |
                                                        |  Answer)          |
                                                        +-------------------+
                                                                  |
                                                                  v
                                                        +-------------------+
                                                        |   Student Query   |
                                                        |   Response        |
                                                        +-------------------+

```
---

## 📂 Repository Structure  
```bash
CS15-Assistant/
├── data/                 # Lecture transcripts and training materials
├── src/                  # Model training, preprocessing, and chatbot logic
├── backend/              # API layer (Flask/Django/FastAPI) with RAG pipeline
├── frontend/             # React interface for student interaction
├── models/               # Fine-tuned / RAG-enabled models
├── README.md             # Documentation
```

## 🚀 Getting Started
1. Clone repository

```bash
git clone https://github.com/your-username/CS15-Assistant.git
cd CS15-Assistant
```

2. Install dependencies
```bash
pip install -r backend/requirements.txt
```
3. Run the backend (RAG + ChatGPT 3.0)
python backend/app.py

4. Launch the frontend

```bash
cd frontend
npm install
npm start
```

## 🛠️ Tech Stack

- vLLM Backbone: ChatGPT 3.0

- Knowledge Retrieval: RAG pipeline (Vector DB + Embeddings)

- Backend: Flask / FastAPI

- Frontend: React.js

- Data: Lecture transcripts & course material

##🎯 Use Case

- Student Q&A on lecture topics

- Reinforcing learning with guided explanations

- Course-specific AI teaching assistant

# 🤝 Contributions

We welcome contributions! Feel free to fork the repo, submit pull requests, or suggest improvements.


Do you want me to also add a **diagram in Markdown (ASCII workflow)** showing how lectures 

# 🧠 CleverDoc System

## 🔍 Overview / Use Case
**Clever Doc System** is an **LLM-powered intelligent document analysis platform** that combines **Retrieval-Augmented Generation (RAG)** with **large language models (LLMs)** to perform deep document understanding, comparison, and visualization.

Users can:
- Upload multiple documents (PDF, DOCX, TXT, etc.)
- Query any uploaded file using natural language
- Compare two files to find similarities, differences, or contextual updates

💡 **Real-World Example:**
A **legal or compliance team** can upload multiple versions of a contract. The system automatically identifies and summarizes the clause changes, deadline updates, or modified obligations.  
Similarly, **researchers** can compare policy drafts or technical reports to track changes and insights over time.

---

## 🧰 Technology Used
| Technology | Purpose |
|-------------|----------|
| **OpenAI API** | LLM-based document analysis, comparison, and Q&A |
| **OpenAI Embeddings** | Converts text into vectors for semantic search |
| **Pinecone** | Vector database for storing and retrieving embeddings |
| **FastAPI** | Lightweight Python backend for API development |
| **Docker** | Containerization for deployment |
| **GitHub Actions (CI/CD)** | Automated build, test, and deployment pipeline |
| **AWS ECR & ECS Fargate** | Cloud infrastructure for scalable deployments |
| **Python + VS Code** | Development environment |
| **python-dotenv** | Secure management of API keys and environment variables |

---

## 🏗️ Architecture Overview
1. **User Interface:** Upload files and submit queries or comparisons  
2. **Backend (FastAPI):** Handles file management, embeddings, and query logic  
3. **RAG Engine:** Retrieves contextually relevant chunks from Pinecone  
4. **LLM Layer (OpenAI):** Generates summaries, differences, and answers  
5. **Storage Layer:** Stores embeddings and processed data (Pinecone + AWS)  
6. **CI/CD Pipeline:** Automated testing and deployment via GitHub Actions  

---

## ⚙️ Key Features
✅ Upload and analyze multiple documents simultaneously  
✅ Query any uploaded file using natural language prompts  
✅ Compare two documents and extract differences in text or meaning  
✅ Retrieve context-aware answers using **RAG**  
✅ Fully **containerized** using Docker for easy deployment  
✅ Cloud-native deployment via **AWS ECS Fargate**  
✅ Automated CI/CD with **GitHub Actions**  
✅ Secure environment management using **python-dotenv**  

---

## 🚀 Future Enhancements
🔹 Implement **authentication and role-based access control (RBAC)**  
🔹 Add a **frontend dashboard (React + Bootstrap)** for visual interaction  
🔹 Integrate **OCR and speech-to-text** for image and audio-based documents  

---



# Gemma Model Document Q&A

## 📌 Project Overview
Gemma Model Document Q&A is an AI-powered web application that allows users to upload PDF documents and ask questions related to the content. The system processes the documents, extracts relevant information, and provides answers using Groq's Llama 3 model and Google's Generative AI Embeddings.

## 🚀 Features
- **PDF Document Processing**: Automatically extracts and splits text from uploaded PDFs.
- **Vector-Based Search**: Uses FAISS for fast and accurate document retrieval.
- **Llama 3 AI-Powered Q&A**: Answers user queries based on document content.
- **Contextual Search**: Provides document excerpts related to the query.
- **Streamlit UI**: Simple and interactive web-based interface.

## 🛠️ Installation
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/Abubakar0011/Documment-Q-A-using-Groq-Gemma.git
   ```
2. **Create a Virtual Environment:**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Set Up API Keys:**
   - Create a `.env` file in the root directory.
   - Add the following keys:
     ```env
     GROQ_API_KEY=your_groq_api_key
     GOOGLE_API_KEY=your_google_api_key
     ```

## 🎯 Usage
1. **Run the Application:**
   ```sh
   streamlit run app.py
   ```
2. **Upload PDFs:** Place your documents in the `./us_census` directory.
3. **Generate Embeddings:** Click the "Documents Embedding" button.
4. **Ask Questions:** Enter your query in the input field and get instant AI-generated answers.

## 📂 Project Structure
```
├── us_census/                # Folder containing PDF documents
├── app.py                    # Main application file
├── requirements.txt          # Required dependencies
├── .env                      # Environment variables (API keys)
└── README.md                 # Project documentation
```

## 📌 Technologies Used
- **Streamlit** – Web UI
- **LangChain** – AI-based document processing
- **FAISS** – Vector search
- **Google Generative AI** – Embeddings
- **Groq (Llama 3)** – AI-powered Q&A

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repo and submit a PR.



📄 RAG Document Q&A With Groq and LLaMA3
This project is a Streamlit web app for performing question answering on research papers using a Retrieval-Augmented Generation (RAG) pipeline. It leverages Groq's LLaMA3 language model and supports Hugging Face or OpenAI embeddings for document indexing.

🔧 Features
Upload and embed documents from the research_papers folder

Vector store creation using FAISS

Ask questions on the embedded documents

Get responses generated using Groq's LLaMA3

Context visibility with document similarity expander

📁 Folder Structure
bash
Copy
Edit
.
├── app_huggingfaceembedding.py  # Uses Hugging Face Embeddings
├── main.py                      # Uses OpenAI Embeddings
├── research_papers/             # Directory to store input PDFs
├── .env                         # Environment file to store API keys
🚀 How to Run
Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name
cd your-repo-name
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Set up your .env file

ini
Copy
Edit
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
HF_TOKEN=your_huggingface_token  # Only required for Hugging Face version
Place your PDFs in the research_papers/ directory.

Run the app

For Hugging Face version:

bash
Copy
Edit
streamlit run app_huggingfaceembedding.py
For OpenAI version:

bash
Copy
Edit
streamlit run main.py
🧠 Technologies Used
*Streamlit

*LangChain

*FAISS

*Groq

*LLaMA3

*OpenAI

*Hugging Face Transformers

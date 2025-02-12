# DeepSeek Based Rag Agent

* DocuMind AI

DocuMind AI is an intelligent document assistant built using Streamlit and LangChain. It allows users to upload research documents in PDF format and ask questions related to the content. The application uses embedding-based retrieval and a language model to generate concise and factual responses.

* Features

📄 PDF Upload: Upload and process research documents in PDF format.

🔍 Document Chunking: Splits large documents into smaller, retrievable chunks.

🧠 Vector Search: Retrieves relevant document sections based on user queries.

🤖 AI-Powered Responses: Uses a language model to generate precise answers.

🎨 Dark-Themed UI: Custom-styled chat interface for a seamless experience.

Installation

Prerequisites

Ensure you have Python 3.8+ installed.

Steps

Clone the repository:

git clone https://github.com/your-repo/documind-ai.git
cd documind-ai

Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate     # On Windows

Install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run app.py

Usage

Upload a PDF document.

Wait for processing to complete.

Ask questions related to the document using the chat input.

Receive AI-generated answers based on document context.

File Structure

📂 documind-ai
├── 📄 app.py                 # Main application script
├── 📄 requirements.txt       # Python dependencies
├── 📂 document_store        # Folder to store uploaded PDFs
└── 📂 assets                 # UI styling and related assets

Technologies Used

Streamlit: Interactive web interface

LangChain: Document processing and retrieval

Ollama LLM: AI-powered question answering

PDFPlumber: PDF text extraction

License

This project is licensed under the MIT License.

Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request.

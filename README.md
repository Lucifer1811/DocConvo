# DocConvo: Explore PDFs Through Conversation

DocConvo is an innovative tool that facilitates natural language interactions for exploring PDF documents. This application leverages LangChain, a powerful library for text processing and retrieval, to enhance the conversational experience.

## Features

- **Conversational Exploration:** Engage in natural language conversations with your PDF documents.
- **Multi-document Support:** Upload and explore insights from multiple PDFs seamlessly.
- **Insightful Responses:** Receive dynamic and informative responses powered by LangChain's advanced natural language processing (NLP) techniques.
- **Hugging Face Integration:** Utilizes Hugging Face models for enhanced language modeling.

## Getting Started

### Prerequisites

- Python 3.x
- Pip (Python package installer)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Lucfer1811/DocConvo.git
    ```

2. Change into the project directory:

    ```bash
    cd your-repository
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

0. create a .env file and add the hugging face api token in the following format:

    ```
    HUGGINGFACEHUB_API_TOKEN=your_api_token
    ```

2. Run the application:

    ```bash
    streamlit run your app.py
    ```

3. Open your web browser and navigate to the provided local URL.

4. Upload PDF documents and start asking questions.

## LangChain Integration

DocConvo incorporates [LangChain](https://langchain.ai/), a versatile text processing library, for efficient document handling. LangChain's features include:

- **Text Splitting:** Efficiently split document text into manageable chunks.
- **Embeddings:** Utilize Hugging Face Instruct Embeddings for advanced text representation.
- **Vector Store:** Create a vector store for optimized document retrieval using FAISS.
- **Conversational Chain:** Implement a Conversational Retrieval Chain for dynamic chat-based interactions.
- **Language Model Hub:** Integrate Hugging Face Hub for language model management.

Explore the power of LangChain alongside DocConvo to unlock a seamless and interactive document exploration experience.

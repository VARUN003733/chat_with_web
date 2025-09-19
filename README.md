# Chat with Websites

Interactively chat with any website using Gemini Pro and LangChain, powered by Streamlit.

## Features

- Loads website content and splits it into chunks for retrieval.
- Uses Gemini Pro for conversational AI and context-aware retrieval.
- Stores website embeddings in a vector database (Chroma).
- Simple Streamlit UI for chatting.

## Setup

1. **Clone the repository**

2. **Install dependencies**
   ```sh
   pip install streamlit langchain langchain-google-genai beautifulsoup4 python-dotenv chromadb google-generativeai
   ```

3. **Configure environment variables**
   - Create a `.env` file with your API keys (e.g., for Google Generative AI).

4. **Run the app**
   ```sh
   streamlit run src/app.py
   ```

## Usage

- Enter a website URL in the sidebar.
- Start chatting with the website content!

## File Structure

- `src/app.py`: Main Streamlit application.
- `.env`: Environment variables (not tracked in git).
- `.idea/`: IDE configuration files.

##
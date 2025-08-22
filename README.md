# LangChain Chat with Search

This project is a **Streamlit-based chatbot** that integrates **LangChain** with OpenAI models to provide intelligent, search-augmented responses. Users can query in natural language, and the bot fetches real-time information using **DuckDuckGo, Arxiv, and Wikipedia**.

## Features
- **OpenAI LLM Integration**: Powered by `gpt-4o-mini` (configurable).
- **Web & Knowledge Tools**: Fetches live data from DuckDuckGo, Arxiv, and Wikipedia.
- **Interactive Chat**: Simple Streamlit chat interface with session-based memory.
- **Custom API Key Input**: Secure input for user’s own OpenAI API key.

## Requirements
Install dependencies via `requirements.txt`:
```bash
pip install -r requirements.txt
```

## Usage
Run the Streamlit app locally:
```bash
streamlit run app.py
```

Enter your **OpenAI API key** in the sidebar, then start chatting!

## File Structure
- `app.py`: Main Streamlit chatbot app.
- `requirements.txt`: Python dependencies.

## Example Queries
- "What is Machine Learning?"
- "Summarize latest research on Transformers from Arxiv."
- "Who is Alan Turing?"

## License
This project is licensed under the MIT License.

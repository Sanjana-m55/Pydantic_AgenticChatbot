# 🔍 Gen AI Search Agent

A Streamlit web application that leverages Groq's LLama 3.1 model and Tavily's search API to provide AI-powered search results.

## 🚀 Features

- Simple, user-friendly interface
- AI-enhanced search responses using LLama 3.1
- Real-time web search capabilities via Tavily
- Clean presentation of search results

## 📋 Requirements

```
pydantic-ai==0.1.3
pydantic-ai-slim[tavily]==0.1.3
streamlit
```

## 🔧 Setup

1. Clone this repository
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Set up your API keys:
   - Get a Groq API key from [Groq](https://console.groq.com)
   - Get a Tavily API key from [Tavily](https://tavily.com)
   - Set them as environment variables or update them in the code

## 🏃‍♂️ Running the Application

```
streamlit run app.py
```

## 📁 Project Structure

- `app.py`: Main Streamlit application
- `agent_utils.py`: Utility functions for the AI agent

## ⚙️ How It Works

1. User enters a search query in the text input field
2. The application leverages Groq's LLama 3.1 model and Tavily's search API
3. Results are processed and displayed in a clean format

## 🔐 API Keys

This project requires two API keys:
- `GROQ_API_KEY`: For access to the LLama 3.1 model
- `TAVILY_API_KEY`: For web search functionality

## 📝 License

MIT License

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

# GenAI Search Agent

A simple yet powerful Generative AI search agent built with Pydantic AI and Streamlit. This application allows users to ask questions and get up-to-date information from the web using the Tavily search API and Groq's LLama 3.1 model.

![GenAI Search Agent](https://raw.githubusercontent.com/pydantic/pydantic-ai/main/docs/img/pydantic-ai-logo.png)

## 🌟 Features

- 🔍 Real-time web search capabilities
- 🤖 Powered by Groq's LLama 3.1 8B Instant model
- 🌐 Uses Tavily search API for accurate and relevant results
- 🚀 Simple and intuitive user interface built with Streamlit
- ⚡ Fast response times

## 📋 Prerequisites

- Python 3.8+
- Groq API key
- Tavily API key

## 🛠️ Installation

1. Clone this repository:
   ```
   git clone <repository-url>
   cd pydantic-ai-agent-main
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your API keys in the `agent_utils.py` file:
   ```python
   os.environ["GROQ_API_KEY"] = "your_groq_api_key"
   TAVILY_API_KEY = "your_tavily_api_key"
   ```

## 🚀 Usage

1. Start the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and navigate to the URL displayed in the terminal (usually http://localhost:8501)

3. Enter your query in the text input field and click "Search"

4. The agent will search the web and provide you with relevant information

## 🧩 Project Structure

- `app.py`: Main Streamlit application file
- `agent_utils.py`: Contains the agent configuration and search functionality
- `requirements.txt`: List of required Python packages
- `Build_Agents_using_Pydantic_AI.ipynb`: Jupyter notebook demonstrating the agent's functionality
- `start_app.txt`: Commands to install dependencies and start the application

## 🔧 How It Works

1. The application uses Pydantic AI to create an agent with the Groq LLama 3.1 model
2. The agent is equipped with the Tavily search tool to fetch information from the web
3. When a user submits a query, the application sends it to the agent
4. The agent processes the query, searches the web using Tavily, and returns the results
5. The results are displayed to the user in a readable format

## 📚 Technologies Used

- [Pydantic AI](https://github.com/pydantic/pydantic-ai): Framework for building AI agents
- [Streamlit](https://streamlit.io/): Web application framework for Python
- [Groq](https://groq.com/): Provider of the LLama 3.1 language model
- [Tavily](https://tavily.com/): Search API for AI applications

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- [Pydantic AI](https://github.com/pydantic/pydantic-ai) for providing the agent framework
- [Streamlit](https://streamlit.io/) for the easy-to-use web application framework
- [Groq](https://groq.com/) for the powerful language model
- [Tavily](https://tavily.com/) for the search API

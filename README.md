# GenAI Search Agent

A simple yet powerful Generative AI search agent built with Pydantic AI and Streamlit. This application allows users to ask questions and get up-to-date information from the web using the Tavily search API and Groq's LLama 3.1 model.

![GenAI Search Agent](https://images.unsplash.com/opengraph/1x1.png?mark=https%3A%2F%2Fimages.unsplash.com%2Fopengraph%2Flogo.png&mark-w=64&mark-align=top%2Cleft&mark-pad=50&h=630&w=1200&blend=https%3A%2F%2Fimages.unsplash.com%2Fphoto-1680783954745-3249be59e527%3Fcrop%3Dfaces%252Cedges%26h%3D630%26w%3D1200%26blend%3D000000%26blend-mode%3Dnormal%26blend-alpha%3D10%26mark-w%3D750%26mark-align%3Dmiddle%252Ccenter%26mark%3Dhttps%253A%252F%252Fimages.unsplash.com%252Fopengraph%252Fsearch-input.png%253Fw%253D750%2526h%253D84%2526txt%253Dai%252Bagent%2526txt-pad%253D80%2526txt-align%253Dmiddle%25252Cleft%2526txt-color%253D%252523000000%2526txt-size%253D40%2526txt-width%253D660%2526txt-clip%253Dellipsis%2526auto%253Dformat%2526fit%253Dcrop%2526q%253D60%26auto%3Dformat%26fit%3Dcrop%26q%3D60%26ixid%3DM3wxMjA3fDB8MXxzZWFyY2h8Nnx8YWklMjBhZ2VudHxlbnwwfHx8fDE3NDQ3NDMwNTR8MA%26ixlib%3Drb-4.0.3&blend-w=1&auto=format&fit=crop&q=60)

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

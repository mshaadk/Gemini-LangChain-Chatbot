# Gemini LangChain Chatbot
Welcome to the Gemini LangChain Chatbot project! This application leverages Google's Gemini LLM to create an interactive conversational agent using Streamlit. The chatbot maintains conversation context, offers creative responses, and features customizable background styling.

## Features
- **Real-time Chat:** Engage in dynamic conversations with an AI chatbot.
- **Conversation Memory:** Utilizes ConversationSummaryMemory to keep track of the conversation history.
- **Customizable Background:** Set a background image and adjust opacity using URL.
- **API Integration:** Connects to Google's Generative AI API (Gemini) for generating responses.

## Installation
To set up and run the chatbot locally, follow these instructions:

### 1. Clone the repository:

```bash
git clone https://github.com/shaadclt/Gemini-LangChain-Chatbot.git
cd Gemini-LangChain-Chatbot
```

### 2. Create and activate a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

### 4. Set up environment variables:

- Create a `.env` file in the project root directory.
- Add your Google API key to the .env file:

```makefile
GOOGLE_API_KEY=your_google_api_key_here
```

### 5. Run the Streamlit app:

```bash
streamlit run app.py
```

### 6. Open your web browser and navigate to the URL provided by Streamlit to start interacting with the chatbot.

## Usage
1. Enter your Google API key in the `.env` file to enable the chatbot.
2. Type your message in the chat input field and click "Send."
3. View the conversation history and responses from the AI.
4. Customize the background by setting the URL and opacity in the code.
   
## Project Structure
`app.py`: Main Streamlit application file.
`requirements.txt`: File listing the required Python packages.
`.env`: File containing environment variables such as the Google API key.
`README.md`: Documentation file for the project.
`LICENSE.txt`: License file

## Dependencies
`streamlit`: For building the web application interface.
`langchain_google_genai`: For interfacing with Google Gemini LLM.
`google.generativeai`: For API configuration.
`streamlit_chat`: For displaying chat messages in Streamlit.
`dotenv`: For loading environment variables from a file.

## License
This project is licensed under the [MIT License](LICENSE.txt).

## Contact
For questions or suggestions, feel free to reach out to [Mohamed Shaad](https://www.linkedin.com/in/mohamedshaad/).

## AI Chatbot with Gradio

This repository contains an interactive AI-powered chatbot built using OpenAI’s GPT models and integrated with Gradio for a user-friendly web interface.

The chatbot supports streaming responses, maintains conversation history, and can be easily customized to suit different use cases such as customer support, personal assistance, or educational Q&A.

**🚀 Features**

Gradio Interface: Simple and responsive UI for chatting in real-time.

Streaming Responses: Messages are streamed token-by-token for a natural typing effect.

Conversation Memory: Maintains chat history for coherent conversations.

Environment Variables: API keys are securely managed via a .env file.

Modular Code: Easy to extend with other LLM providers (Anthropic, Google, etc.).

**🛠️ Installation**

Clone the repository:

git clone https://github.com/your-username/AI-Chatbot-with-Gradio.git
cd AI-Chatbot-with-Gradio


Create a virtual environment and install dependencies:

pip install -r requirements.txt

**🔑 Setup**

Create a .env file in the project root:

touch .env


Add your API keys inside:

OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key   # optional
GOOGLE_API_KEY=your_google_api_key         # optional

**▶️ Usage**

Run the chatbot locally:

python app.py


or open the Jupyter notebook:

jupyter notebook AI_Chatbot_with_Gradio.ipynb


Once started, Gradio will provide you with a local URL and a public shareable link to interact with the chatbot.

**📂 Project Structure**
AI_Chatbot_with_Gradio/
│── AI_Chatbot_with_Gradio.ipynb   # Main Jupyter notebook
│── requirements.txt               # Dependencies
│── app.py                         # (Optional) Run standalone chatbot
│── .env.example                   # Example environment variables
│── README.md                      # Project documentation

**📌 Roadmap**

 Add support for multiple LLMs (Anthropic, Gemini, etc.)

 Enhance UI with themes and chat history export

 Deploy on Hugging Face Spaces or Streamlit Cloud

🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit pull requests for improvements.

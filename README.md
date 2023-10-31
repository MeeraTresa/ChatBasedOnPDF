# ChatBasedOnPDF
RAG Chatbot with PDFs

The MultiPDF Chat App is a Python application that allows you to chat with multiple PDF documents. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. 
This app utilizes a language model to generate accurate answers to your queries. Please note that the app will only respond to questions related to the loaded PDFs.

Created using tutorial by **[Alejandro AO](https://youtu.be/dXxQ0LR-3Hg).**

To install the ChatBasedOnPDF App, please follow these steps:

Clone the repository to your local machine.

Install the required dependencies by running the following command:
  ```
  pip install -r requirements.txt
  ```

Obtain an API key from OpenAI and add it to the .env file in the project directory.
```commandline
OPENAI_API_KEY=your_secrit_api_key
```

Obtain HuggingFace Hub's Access token and add it to the .env file in the project directory.
```commandline
HUGGINGFACEHUB_API_TOKEN=your_secrit_token
```

## Usage
-----
To use the MultiPDF Chat App, follow these steps:

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the `.env` file.

2. Run the `main.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ```

3. The application will launch in your default web browser, displaying the user interface.

4. Load multiple PDF documents into the app by following the provided instructions.

5. Ask questions in natural language about the loaded PDFs using the chat interface.
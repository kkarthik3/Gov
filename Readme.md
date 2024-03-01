# Streamlit Chatbot with CSV Data using GEMMA or Google Genrative-AI 🤖🦜

## Overview
This project demonstrates the development of a conversational chatbot using Streamlit, which interacts with CSV data using Llama2 language model. The chatbot assists users with queries related to a particular context provided by the CSV data.

# Download and Install Ollama

To use Ollama, follow these steps:

1. **Download and Install Ollama:**
   - Ollama can be installed on various platforms, including Windows Subsystem for Linux (WSL). 
   - You can download Ollama from [here](https://ollama.com/download).

2. **Fetch Available LLM Model:**
   - Use the command `ollama pull <name-of-model>` to fetch an available LLM model.
   - For example, to fetch the Gemma or Llama-7b model, you would use: 
     ```
     ollama pull gemma
     ```

3. **View Available Models:**
   - To view a list of available models, use the model library.
   - You can check the available models in the [Ollama Model Library](https://ollama.com/library).


## Components Used
- **Streamlit**: Streamlit is used for creating interactive web applications with simple Python scripts.
- **Gemma**: GEMMA is a language model utilized for generating conversational responses.
- **Hugging Face Sentence Transformers**: These are used for generating embeddings for text data.
- **FAISS Vector Store**: FAISS is employed for similarity search based on text embeddings.
- **Google Generative AI**: A Google Generative AI model is used for conversation generation.
- **CSV Loader**: CSV Loader loads the CSV data containing the context for the chatbot.
- **Chat History Management**: Chat history is managed to maintain a conversation context.

## Functionality
- **Loading the Model**: The necessary models and data are loaded, including Llama2, embeddings, and the FAISS vector store.
- **Conversational Chain**: A conversational chain is set up to handle user queries and provide responses based on the context.
- **User Input and Output Handling**: User inputs are accepted via a text input field, and the chatbot responds accordingly.
- **Chat History**: Chat history is maintained to display past conversations.

## Implementation
- **User Interface**: The interface consists of a text input field for user queries and a chat history container to display conversations.
- **Input Processing**: User queries are processed, and responses are generated using the conversational chain.
- **Chat History Display**: The chat history is displayed in the UI, including user queries and bot responses.

## Usage
1. Install the necessary dependencies.
2. Run the Streamlit application.
3. Input queries in the text field to interact with the chatbot.
4. View the conversation history displayed in the UI.

## Acknowledgements
- **Author 1**: Karthikeyan K (GitHub: [kkarthik3](https://github.com/kkarthik3))
- **Author 2**: Mohana Priya N (GitHub: [mohanapriya1706](https://github.com/mohanapriya1706))

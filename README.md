# Chat GPT Web App

This project is a simple web app that uses the GPT-3 model from OpenAI to simulate a conversation with a chatbot. It is built using the Gradio library, which allows for easy deployment of machine learning models as web applications.

## Getting Started

1.  Clone the repository and navigate to the project directory.
2.  Create a virtual environment and activate it.
3.  Install the dependencies by running `pip install -r requirements.txt`.
4.  Replace `YOUR_API_KEY` with your OpenAI API key in the `Dockerfile`.
5.  Build the Docker image by running `docker build -t chat-gpt-app .`.
6.  Run the container by running `docker run -p 7860:7860 chat-gpt-app`.
7.  Open a web browser and navigate to `http://0.0.0.0:7860/` to access the application.

## Usage

The application will start with a prompt asking the user to start a conversation with the AI. The user can type in a message and click the "SEND" button to receive a response from the AI. The conversation history will be displayed on the page, and the user can continue the conversation by typing in a new message and clicking the "SEND" button again.

## Note

This project is for educational purpose only and should not be used for any commercial or production use case.

Also, The API Key that you are using should be kept private and should not be shared with anyone.
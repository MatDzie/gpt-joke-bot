# Joke Chatbot using OpenAI GPT-3.5 and Gradio
This repository contains a simple Python program that generates jokes based on user input using OpenAI GPT-3.5 and Gradio. The application creates a web-based user interface for users to enter a topic and receive a joke related to that topic.

![joke-bot](https://user-images.githubusercontent.com/7393868/232312690-2c07b28f-f5e1-43b5-b741-9bd808e31585.PNG)

## Installation
To run the joke chatbot, first clone the repository and navigate to the project folder:

```
git clone https://github.com/MatDzie/joke-chatbot.git
cd joke-chatbot
```

Install the necessary Python libraries:
```
pip install gradio openai
```
## Set up OpenAI API Key
Make sure you have an API key for OpenAI. You can get one from https://beta.openai.com/signup/.

Set up your OpenAI API key as an environment variable or directly include it in your Python code:

```
export OPENAI_API_KEY="your_api_key_here"
```

## Usage
To launch the joke chatbot, run the Python script:

```
python joke_chatbot.py
```
A web interface will open in your default web browser. Enter a topic for the joke and click "Submit". The generated joke will appear below.

## Customization
You can customize the cost per token in the joke_chatbot.py script according to your OpenAI API pricing plan by modifying the cost_per_token variable.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to adapt the above example to match your GitHub repository URL and include any additional information or screenshots that you find relevant. Save this content in a README.md file in your repository to have it displayed on the GitHub project page.

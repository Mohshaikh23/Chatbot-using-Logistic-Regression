# Chatbot Project

This is a simple chatbot project built using Streamlit, scikit-learn, and NLTK. The chatbot responds to user inputs with predefined responses based on different intents.

![Screenshot of chatbot](https://github.com/Mohshaikh23/Chatbot-using-Logistic-Regression/blob/main/chatbot_screenshot.png?raw=true)

## Prerequisites

Before running the chatbot, make sure you have the necessary libraries installed. You can install them using the following command:

```bash
pip install -r requirements.txt
```

## Usage

Clone the repository:

```bash
git clone https://github.com/Mohshaikh23/Chatbot-using-Logistic-Regression.git
cd Chatbot_Project
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the chatbot:

```bash
streamlit run chatbot.py
```

Type a message in the input box and press Enter to start the conversation with the chatbot.

## About the Chatbot
The chatbot uses a basic natural language processing approach to match user inputs to predefined intents and provide relevant responses. It uses TF-IDF vectorization and a Logistic Regression classifier for intent prediction.

## Intents
The chatbot responds to various intents, including greetings, goodbyes, thanks, and more. You can find the list of intents and corresponding patterns in the intents dictionary in the chatbot.py script.

## Further Enhancements
Feel free to enhance the chatbot's capabilities by adding more intents, improving the response selection logic, or integrating more advanced NLP techniques.

License
This project is licensed under the MIT License.

Feel free to reach out if you have any questions or suggestions!
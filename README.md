# Automated-Report-Generation

*COMPANY*: CODETECH IT SOLUTIONS 

*NAME*:SANJAI KRISHNAN S 

*INTERN ID*:CTO4DG3176

*DOMAIN*:PYTHON PROGRAMMING 

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTOSH

*PROCESS DESCRIPTION*:

The development of the AI Chatbot using Natural Language Processing (NLP) follows a structured approach that combines fundamental programming concepts with essential elements of human language understanding. The chatbot, created by Sanjai Krishnan. S as part of Task 3 during an internship at Codetech IT Solutions, was designed to simulate basic human-like conversations using simple NLP and rule-based techniques. The project was implemented using Python, leveraging libraries such as NLTK, Regex, and Datetime.


---

📌 Step-by-Step Development Process:

1. Problem Understanding and Objective Setting

The primary goal of this task was to build a beginner-level AI chatbot that can understand user input and reply with appropriate responses. The chatbot was not intended to use advanced machine learning, but rather to rely on basic NLP tools and predefined rules to detect intents and give dynamic responses.

2. Library Setup and Environment Configuration

The chatbot was built in a Python environment. The essential libraries used include:

NLTK (Natural Language Toolkit) for tokenizing and preparing user input.

Regex (Regular Expressions) for identifying patterns and keywords in user messages.

Datetime to provide real-time system data such as current time.


The project begins with downloading necessary NLTK resources, such as the 'punkt' tokenizer, which is used for breaking down sentences into words or tokens.

3. Designing the Chat Interface and Response System

A clear and user-friendly intro message is printed to welcome users and set the tone. The core of the chatbot lies in a dictionary named responses, which stores multiple categories of replies including:

Greetings

Farewells

Time inquiries

Gratitude responses

Bot identity

Default fallback responses


By using randomized selection (random.choice()), the chatbot provides slightly varied replies for the same intent, making interactions less robotic.

4. Intent Recognition Using Regex

The chatbot uses a function called get_intent() to classify user input into different intents. This is achieved using regular expressions that search for keywords in user messages. For example:

Words like “hi”, “hello”, or “hey” trigger a “greeting” intent.

Phrases like “thank you” or “thanks” map to a “thanks” intent.

Asking “what time is it?” invokes the “time” intent.


This pattern matching strategy keeps the bot lightweight and responsive, ideal for beginners to understand how NLP works on a structural level.

5. Conversation Flow – Chat Loop

The main chat loop continuously takes user input, identifies the intent using get_intent(), and prints a relevant response. If the intent is “goodbye”, the loop breaks and a closing message is displayed.

6. Project Closure and Output

Upon exiting, the chatbot prints a thank-you message along with credits to the intern and the hosting organization. This gives the chatbot a professional touch and reinforces branding.

*OUTPUT*:

<img width="1024" height="1536" alt="Image" src="https://github.com/user-attachments/assets/17a0d302-093e-425c-b741-e3eb4c189526" />

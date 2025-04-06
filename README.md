# Security+ Quizzer (v1)
----------------------

A terminal-based Security+ study tool powered by OpenAI's GPT-4o.

This app generates multiple-choice questions based on Security+ SY0-701 domains using the OpenAI API. Great for solo studying or brushing up on key topics with dynamic content.

## Features
--------
- Choose a domain or general Security+ topic
- Get AI-generated multiple-choice questions
- All questions follow the SY0-701 exam format
- Built-in .env setup prompt if your API key is missing

## Tech Stack
----------
- Python 3
- OpenAI Python SDK (v1)
- python-dotenv
- Git & GitHub CLI

## Setup Instructions
------------------

1. Clone the repo:
   git clone https://github.com/CodedByGoose/sec-quizzer.git
   cd sec-quizzer

2. Install dependencies (if you're using a virtual environment):
   pip install openai python-dotenv

3. If you haven’t run it yet, the script will ask for your OpenAI API key and create a .env file for you.  
   You can also create it manually. Paste the following into a .env file in the root directory:

   OPENAI_API_KEY=your-api-key-here

4. Run the quiz:
   python quizzer.py

### Future Plans
------------
- Let users answer and check if they’re correct
- Score tracking
- Option to explain answers
- Add difficulty levels or question types
- Build a web version (Flask)

#### License
-------
MIT License. See LICENSE file for details.

##### Made by @codedbygoose
----------------------
If you found this helpful or have suggestions, feel free to fork it, star it, or reach out!

# ChatGPTClone
This is a ChatGPT Clone, using OpenAI API to generate responses and GPT-4 as model technology.

## Prerequisites
- Django framework installed (`pip3 install django` for Mac OS/Linux, `pip install django` for Windows)
- Create an OpenAI API key on the website (you need to pay a minimum of 5$ for this to work) -> `https://platform.openai.com/account/api-keys`

## Setup
- Set your API key as an environment variable. To do this run in terminal -> `export $OPENAI_API_KEY='your_key'` where you replace 'your_key' with your actual key

## Running the app
- To run the app, run the following command from app's root directory -> `python3 manage.py runserver` for MacOS/Linux, `python manage.py runserver` on Windows
- Enter `localhost:8000` in your browser
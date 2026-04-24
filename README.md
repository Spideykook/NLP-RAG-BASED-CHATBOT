# NLP RAG Chatbot (Django)

This project is a chatbot built using Django that tries to give better responses by combining basic NLP with a retrieval-based approach (RAG).
The idea was to move beyond simple rule-based replies and make the bot respond more contextually.

## What it does

* Takes user input through a simple chat interface
* Processes the query using NLP logic
* Retrieves relevant information and generates a response
* Returns a more meaningful answer compared to basic chatbots

## Tech used

* Django (backend)
* Python (core logic)
* HTML/CSS/JS (frontend)
* SQLite (default DB)

## Running it locally

Clone the repo:
git clone https://github.com/Spideykook/NLP-RAG-BASED-CHATBOT.git

Go into the folder:
cd NLP-RAG-BASED-CHATBOT

Create a virtual environment and activate it:
python -m venv env
env\Scripts\activate

Install dependencies:
pip install -r requirements.txt

Run migrations:
python manage.py migrate

Start the server:
python manage.py runserver

Then open http://127.0.0.1:8000/ in your browser.

## Notes

This is still a work in progress. The main focus was understanding how RAG-style systems can be integrated into a Django app rather than building a perfect chatbot.

## Future scope

* Improve response quality
* Add better UI
* Store chat history
* Try integrating better models/APIs



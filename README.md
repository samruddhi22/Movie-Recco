# Movie-Recco
This is an django and graphql movie recommendation system


## Setting up

Clone this repository, and in the directory follow these steps:

# Create virtual environment
python3 -m venv env
# Activate virtual environment
. env/bin/activate
# Install dependencies
pip install -r requirements.txt
# Run DB migration
python manage.py migrate
# Optional: load test data
python manage.py loaddata movies.json
# Run the application
python manage.py runserver


If you go to http://127.0.0.1:8000/graphql/, you'll be able to interact with the API there.

# Country-Weather-Api
A country weather API


Country & Weather Information App

This is a simple Flask web app that lets you choose a country and see its capital, flag, population, and current weather. It uses two online services:

REST Countries API → Provides country details

WeatherAPI → Gives real-time weather updates


How It Works

1. You open the website and select a country from a dropdown list.


2. The app finds details about the selected country, like its capital and population.


3. It then checks the weather in that capital city.


4. Finally, it shows the country's name, flag, capital, population, and current weather.



How to Set It Up

Step 1: Install Python and Flask

Make sure you have Python installed. Then, open a terminal and run:

python -m venv venv  # Creates a virtual environment  
source venv/bin/activate  # Activates the environment (Windows: `venv\Scripts\activate`)  
pip install Flask requests  # Installs Flask and Requests

Step 2: Get a Weather API Key

1. Go to WeatherAPI.


2. Sign up and get a free API key.


3. Open app.py and replace YOUR_API_KEY with your actual key.



Step 3: Run the App

Run this command in the terminal:

python app.py

Then, open your browser and go to http://127.0.0.1:5000

What’s Inside?

CountryWeatherApp/  
│── templates/        # HTML files  
│   ├── index.html    # Main webpage  
│── app.py            # Main Flask app  
│── requirements.txt  # List of needed Python packages  
│── README.md         # This file

What You Need

Python 3

Flask (for running the web app)

Requests (for getting country and weather data)


This is a great beginner-friendly project for learning Flask, APIs, and basic web development!


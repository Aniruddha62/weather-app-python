# Weather App (Python)

## Overview

This project is a command-line Weather Application built using Python. It fetches real-time weather data for a given city using a public weather API and provides both text and voice output.

The application runs in a loop, allowing users to check weather information for multiple cities until they choose to exit.

This project was built to practice working with APIs, JSON data handling, and integrating text-to-speech functionality in Python.

## Features

- Fetch real-time weather data using API
- Display temperature, wind speed, precipitation, and humidity
- Voice output using Windows Text-to-Speech
- Continuous input loop until user exits
- Simple command-line interface

## Tech Stack

- Python
- requests
- json
- win32com.client (Windows TTS)

## How It Works

1. User enters the name of a city.
2. The application sends a request to the weather API.
3. The JSON response is parsed.
4. Relevant weather details are extracted.
5. Weather information is printed and spoken aloud.
6. User can exit by entering `0`.

## Installation

Note: This application works only on Windows OS because it uses Windows Text-to-Speech.

## How to Run

Enter the city name when prompted.

Enter `0` to exit the program.

## Learning Outcome

While building this project, I practiced:

- Working with REST APIs
- Parsing JSON data in Python
- Handling user input and loops
- Integrating Windows Text-to-Speech
- Extracting and formatting structured data

## Future Improvements

- Add error handling for invalid city names
- Hide API key using environment variables
- Create a GUI version
- Make cross-platform version without Windows dependency

## 👨‍💻 Author

**ANIRUDDHA BHATTACHARYYA**

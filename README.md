# Gemini_Info_Extractor
Gen AI Project

This project leverages the Google Generative AI to create a simple Q&A application. Users can input a question, and the application will return a response generated by the Gemini model.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)


## Features
- Simple Q&A interface
- Uses Google Generative AI (Gemini model) to generate responses

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Gemini_Info_Extractor.git
    cd Gemini_Info_Extractor
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    env\Scripts\activate  # On Windows
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up your Google API key:
    - Create a `.env` file in the project directory.
    - Add your Google API key to the `.env` file:
      ```
      GOOGLE_API_KEY=your_google_api_key
      ```

## Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. In the Streamlit interface:
    - Enter your question in the input box.
    - Click the "Ask the question" button to get a response from the Gemini model.

## Requirements

- Python 3.x
- streamlit
- google-generativeai
- python-dotenv



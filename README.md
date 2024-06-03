# Gemini_Info_Extractor
GEN AI Project

This project leverages Google Generative AI to create a versatile Q&A application. Users can ask questions in text format and upload images to get responses based on the content of the images.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)

## Features
- Ask any question in text format
- Upload an image and ask questions related to the image
- Generate responses using Google Generative AI (Gemini model)

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

1. Run the Streamlit app for text queries:
    ```bash
    streamlit run app.py
    ```

2. In the Streamlit interface:
    - Enter your question in the input box.
    - Click the "Ask the question" button to get a response from the Gemini model.

3. Run the Streamlit app for image queries:
    ```bash
    streamlit run vision.py
    ```

4. In the Streamlit interface:
    - Enter your input prompt in the input box (optional).
    - Upload an image using the file uploader.
    - Click the "Tell me about the image" button to get a response from the Gemini model.

## Requirements

- Python 3.x
- streamlit
- google-generativeai
- python-dotenv







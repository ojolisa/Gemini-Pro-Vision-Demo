# Gemini Pro Vision Demo

This repository contains a Streamlit web application that demonstrates the capabilities of Google's Gemini Pro Vision model. The app allows users to upload an image and query the model for descriptive content related to the image. This README file provides instructions for setting up and using the application, along with an explanation of the code.

## Features

- **Upload Images:** Users can upload `.jpg`, `.png`, or `.jpeg` image files.
- **Text Queries:** Users can enter text queries to ask about the uploaded images.
- **Generative AI Integration:** The app integrates with Google's Gemini Pro Vision model to generate descriptive content based on the uploaded image and user queries.

## Prerequisites

- Python 3.7 or later
- Streamlit
- PIL (Python Imaging Library)
- Google's Generative AI library (`google-generativeai`)
- Jupyter's `IPython` library

## Setup

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/gemini-pro-vision-demo.git
    cd gemini-pro-vision-demo
    ```

2. **Install the required packages:**
    ```sh
    pip install streamlit pillow google-generativeai ipython
    ```

## Running the Application

To run the Streamlit application, use the following command:
```sh
streamlit run app.py

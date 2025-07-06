# MemeMuse
MemeMuse is an AI-powered tool that identifies viral internet trends and meme subcultures in real-time, then generates meme that creatively integrate your brand or product — tailored for specific audiences and platforms. MemeMuse taps into trending humor and formats.

# Features

Supports multiple meme templates (Drake Hotline Bling, Distracted Boyfriend, etc.)
Uses Google Gemini API for text generation
Adds text to meme images using PIL (Python Imaging Library)
Environment variable management with python-dotenv

# Prerequisites

Python 3.11+
Google Gemini API key (set as GEMINI_API_KEY in environment variables or Kaggle secrets)
Fonts: DejaVu fonts (included in most systems or installed via apt-get install fonts-dejavu)

# Installation

Clone the repository:git clone <repository-url>
cd meme_generator


Install dependencies:pip install -r requirements.txt


# Set up your Gemini API key:
Create a .env file in the project root and add:GEMINI_API_KEY=your_api_key_here


Alternatively, if using Kaggle, set the GEMINI_API_KEY in Kaggle secrets.



# Usage

Open the meme_generator.ipynb notebook in Jupyter or Kaggle.
Run the cells to install dependencies and set up the Gemini API.
Select a meme template and provide text inputs to generate a meme.

Project Structure

meme_generator.ipynb: Main Jupyter notebook with the meme generator code
requirements.txt: List of Python dependencies
README.md: Project documentation
.gitignore: Git ignore file for excluding unnecessary files

Notes

The project is designed to run in environments like Kaggle with GPU support.
Ensure internet access is enabled for downloading meme template images.
The Gemini API requires a valid API key from https://aistudio.google.com/app/apikey.

License
MIT License

# AI-Powered-Time-Capsule-Personalized-Memories-Messages-and-Predictions
The **AI-Powered Time Capsule** is a unique project that combines artificial intelligence, face recognition, and text generation to create a time capsule for users. It allows users to store memories, generate personalized birthday messages, predict their future, and more. 


# AI-Powered Time Capsule

The **AI-Powered Time Capsule** is a unique project that combines artificial intelligence, face recognition, and text generation to create a time capsule for users. It allows users to store memories, generate personalized birthday messages, predict their future, and more. All data is saved in a **JSON** format for easy retrieval and personalization in the future.

## Features

- **Emotion Recognition:** Uses AI to detect emotions from facial images and incorporate them into the user's time capsule.
- **Personalized Birthday Messages:** AI-generated messages tailored to the user's name and zodiac sign.
- **Future Predictions:** Provides predictions about the user's life or career in the future (e.g., 10 years ahead).
- **Time Capsule Data:** All data (images, messages, predictions) is saved in a **JSON file**, enabling future access and viewing.
- **Interactive User Experience:** Upload images and receive generated text messages and predictions based on your inputs.

## Tech Stack

- **Python:** The primary programming language used for the project.
- **Transformers (Hugging Face):** A library for implementing GPT-2 model-based text generation.
- **OpenCV:** Used for face detection and emotion recognition tasks.
- **Pandas:** Helps with handling and processing datasets (e.g., for birthdays).
- **JSON:** Used for saving and reading data into and out of the time capsule.

## Installation

Follow these steps to get started with the project:

1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/AI-Powered-Time-Capsule.git
   cd AI-Powered-Time-Capsule

2.Create a virtual environment and install dependencies:
python -m venv tf_env
source tf_env/bin/activate  # On Windows, use `tf_env\Scripts\activate`
pip install -r requirements.txt

3.Download models like GPT-2 if you don't have them already:
transformers-cli login
transformers-cli download openai-community/gpt2

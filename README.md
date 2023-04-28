# Sheldon Chatbot

A chatbot that imitates the speech style and humor of Sheldon Cooper from the popular TV show, The Big Bang Theory.

## Overview

Sheldon Chatbot uses the GPT-3 AI model by OpenAI to generate responses that mimic Sheldon Cooper's unique way of speaking, including his catchphrases and humor. The chatbot provides an engaging and entertaining conversational experience for fans of the show.

## Features

- Conversational interface that mimics Sheldon Cooper's speech style
- Uses catchphrases and humor from the show
- Built with Python and Flask web framework
- Integrates with OpenAI's GPT-3 model for generating responses

## Setup and Installation

To set up and run the Sheldon Chatbot, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/RimaBuilds/sheldon-chatbot.git
```

2. Navigate to the project folder:

```bash
cd sheldon-chatbot
```

3. Install the required Python packages:

```bash
pip install -r requirements.txt
```

4. Set up your OpenAI API key as an environment variable:

```bash
set OPENAI_API_KEY="your_api_key_here"
```

Replace `your_api_key_here` with your actual OpenAI API key.

5. Run the Flask application:

```bash
python app.py
```

6. Open a web browser and navigate to `http://127.0.0.1:5000/` to access the Sheldon Chatbot interface. Start chatting and enjoy interacting with the chatbot!

## Usage

Once the Sheldon Chatbot is running, you can interact with it by typing your messages in the input field and clicking the "Send" button. The chatbot will respond with messages that resemble Sheldon Cooper's speech style and humor.

To make the chatbot's responses more random, you can adjust the temperature and presence_penalty values in the `generate_response` function within the `app.py` file:

```python
temperature = 1.0  # Increase this value for more randomness (e.g., 1.5)
presence_penalty = 0.5  # Decrease this value for more randomness (e.g., 0.3)
```

Higher temperature values will make the output more diverse and creative, while lower presence_penalty values will encourage the model to use the Sheldon Cooper persona more often. Adjust these values as needed to achieve the desired level of randomness in the chatbot's responses.

After making changes, save the `app.py` file and restart the Flask application to apply the changes.

## Acknowledgments

The background image used in the CSS is created by Midjourney ai.
The `sheldon.txt` file contains scripts from Sheldon Cooper's episodes in The Big Bang Theory, sourced from the [Big Bang Theory Transcripts](https://bigbangtrans.wordpress.com/) website.

## Contributing

I made this with chatgpt for fun but if you can make it any funnier :P

Contributions to the Sheldon Chatbot project are welcome! Please feel free to submit issues, feature requests, and pull requests on GitHub.

## License

This project is licensed under the [MIT License](LICENSE).

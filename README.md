# AI Helper Bot

This project is an AI-powered chatbot implemented using the aiogram library and the OpenAI GPT-3.5 Turbo API. The chatbot interacts with users in a messaging platform and provides various functionalities.

## Key Features:

Command Help: Users can use the '/commands' or '/help' command to get a list of available commands and a brief description of each command.

Weather Information: By using the '/weather' command, users can retrieve the current weather information.

Currency Exchange Rates: The '/currency' command enables users to obtain the latest currency exchange rates.

Text Translation: Users can translate text to another language using the '/translate' command.

Random Jokes: The '/joke' command generates and delivers a random joke to entertain users.

Image Generation: With the '/image' command, users can request the chatbot to generate an image based on the provided description. The chatbot utilizes the OpenAI Image API to generate the image.

## Usage:

Start the chatbot by sending the '/start' command. The bot will greet the user and provide instructions on how to use the available commands.

Users can interact with the chatbot by sending text messages. The chatbot processes the user's message and generates a response using the OpenAI Chat API.

The chatbot supports continuous conversation by maintaining the message history for each user. Previous messages from the user are considered in generating responses.

If the chatbot encounters an error related to memory limitations, users can send the '/newtopic' command to start a new conversation topic.

### Note: The chatbot may take a short delay to respond as it processes the user's request and generates a suitable response.

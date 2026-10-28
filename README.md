# AI Video Transcription and Summarization Telegram Chatbot
[video](https://drive.google.com/file/d/1DzI9ai0sQvNcIeZCab9Nq2CCD5Rx1jGk/view?usp=sharing)
## About the Project
This project is an AI-powered Telegram chatbot built using n8n and the Google Gemini API. It accepts YouTube video links, retrieves their transcripts, generates summaries, and allows users to ask follow-up questions about the video through Telegram.

## Features
- Accepts YouTube video links through Telegram.
- Retrieves video transcripts using a transcript API.
- Generates summaries using Google Gemini.
- Answers follow-up questions based on the video's content.
- Stores transcripts and summaries for continued conversations.
- Handles errors when transcripts or API services are unavailable.

## Technologies Used
- n8n
- Google Gemini API
- Telegram Bot API
- Supadata API
- n8n Data Tables

## How It Works
1. The user sends a YouTube video link to the Telegram bot.
2. The workflow retrieves the transcript.
3. Gemini generates a summary of the video.
4. The bot sends the summary to Telegram.
5. The transcript and summary are stored for later reference.
6. The user can ask questions about the video, and the chatbot responds using the saved context.

## Requirements
- n8n account
- Telegram bot and bot token
- Google Gemini API key
- Transcript API key

## Setup
1. Create a Telegram bot using BotFather.
2. Configure Telegram credentials in n8n.
3. Add your Gemini and transcript API credentials securely.
4. Import or build the n8n workflow.
5. Configure the required nodes and database.
6. Test the workflow by sending a YouTube video link to the bot.

## Security
Store all API keys in n8n credentials. Never publish tokens or API keys in the repository.

## Future Improvements
- Support for additional video platforms.
- Automatic generation of quizzes and notes.
- Export summaries as PDF files.
- Improved conversation memory and multilingual support.

## Author
Student Project

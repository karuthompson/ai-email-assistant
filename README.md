# AI-Email-Assistant

This project is a smart email assistant built in Google Colab using Python, Gmail API, and OpenAI GPT-3.5.

It:

* Connects to your Gmail and reads unread emails
* Summarizes each message
* Identifies what action needs to be taken
* Drafts a professional reply using AI

## How It Works

1. Authenticate with Gmail using OAuth
2. Use OpenAI to summarize, extract actions, and write replies
3. Outputs results directly in the notebook

## Setup

1. Clone this repo
2. Upload your `credentials.json` (from Google Cloud)
3. Run the notebook in Google Colab

## Technologies

* Python
* OpenAI API (`gpt-3.5-turbo`)
* Gmail API (via Google Cloud OAuth)
* Google Colab

## Note

This is an MVP project for showcasing fast prototyping and AI integration. It does not send replies automatically (yet) — safety first!

## License

MIT

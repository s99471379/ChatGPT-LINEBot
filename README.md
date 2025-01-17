# ChatGPT-LINEBot

This project is a LINE chatbot built using the **ChatGPT API**. The bot enables users to interact with ChatGPT directly via LINE, providing conversational AI capabilities in a seamless messaging experience.

---

## Features

- **Natural Language Processing**: Interact with ChatGPT for conversational AI.
- **LINE Integration**: Fully integrated with LINE Messaging API.
- **Lightweight**: No backend server required; communicates directly with LINE and ChatGPT API.

---

## Technology Stack

- **API**: OpenAI's ChatGPT API
- **Messaging Platform**: LINE Messaging API

---

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/s99471379/ChatGPT-LINEBot.git
   cd ChatGPT-LINEBot
   ```

2. Configure environment variables:
   - Create a `.env` file in the project directory.
   - Add the following variables:
     ```env
     LINE_CHANNEL_ACCESS_TOKEN=<Your LINE Channel Access Token>
     LINE_CHANNEL_SECRET=<Your LINE Channel Secret>
     OPENAI_API_KEY=<Your OpenAI API Key>
     ```

3. Deploy to your preferred serverless platform or hosting service.

---

## Usage

- Add the LINE bot as a friend using the QR code or LINE bot ID.
- Start a conversation, and the bot will respond using ChatGPT's API.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Acknowledgments

This project was inspired by the capabilities of OpenAI's ChatGPT and LINE's Messaging API. Special thanks to the developers and communities that made these tools accessible and easy to integrate.

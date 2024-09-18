# 📞 Story Quilt Bot Voice Application

Welcome to the **Story Quilt Bot Voice Application**! This FastAPI-based project enables you to make voice calls, transcribe the audio, and generate follow-up questions using the Twilio and OpenAI APIs.

## 📄 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🌟 Overview

This application allows you to make calls to users, ask them a set of pre-defined questions to record a story, and then transcribe their responses using OpenAI's Whisper API. It also intelligently generates follow-up questions based on the transcribed text to gather more information.

## ✨ Features

- **Automated Calls:** Initiates calls to users with pre-defined questions.
- **Voice Transcription:** Uses OpenAI's Whisper API to transcribe recorded responses.
- **Dynamic Question Generation:** Generates follow-up questions based on the initial responses.
- **Twilio Integration:** Seamlessly integrates with Twilio for voice call functionalities.
- **User Interaction:** Engages users through interactive voice responses.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following:

- Python 3.6 or later installed.
- Twilio account and API keys.
- OpenAI API key.
- `dotenv` package configured with necessary environment variables.

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/story-quilt-bot
   ```

2. **Navigate to the project directory:**

   ```sh
   cd story-quilt-bot
   ```

3. **Create and activate a virtual environment:**

   - On Windows:
     ```sh
     python -m venv venv
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```sh
     python -m venv venv
     source venv/bin/activate
     ```

4. **Install the required packages:**

   ```sh
   pip install -r requirements.txt
   ```

### Configuration

Create a `.env` file in the root directory with the following environment variables:

- `TWILIO_ACCOUNT_SID`
- `TWILIO_AUTH_TOKEN`
- `TWILIO_PHONE_NUMBER`
- `OPENAI_API_KEY`

## 🎉 Usage

Once installed and configured, you can start the application to make calls and transcribe responses. Customize the set of pre-defined questions and the generation of follow-up questions to fit your needs.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

Happy coding! 🚀
```

This `README.md` file is designed to be user-friendly and attractive, highlighting the key aspects of your project without diving into the code.
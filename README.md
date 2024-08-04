# HelloBOT.AI

HelloBOT.AI is an AI-powered voice assistant that listens to prompts and responds intelligently. It leverages the Gemini Pro 1 latest OpenAI API and Faster Whisper for speech recognition. The assistant activates on hearing "Hello" and processes the input to provide accurate responses.

## Features

- Voice Recognition: Uses the `speech_recognition` library and `Faster Whisper` for efficient and accurate speech-to-text conversion.
- AI Responses: Utilizes the Gemini Pro 1 latest OpenAI API to generate intelligent responses.
- Environment Management: Uses `dotenv` for managing environment variables.
- Audio Handling: `pyaudio` for capturing and playing audio.

## Installation

1. Clone the repository
    ```bash
    git clone https://github.com/yourusername/HelloBOT.AI.git
    cd HelloBOT.AI
    ```

2. Create a virtual environment
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies
    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables
    Create a `.env` file in the root directory and add your OpenAI API key and other necessary configurations.
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

## Usage

1. Run the application
    ```bash
    python app.py
    ```

2. Interact with HelloBOT.AI
    - Say "Hello" to activate the bot and then speak your prompt.

## Dependencies

- `speech_recognition`
- `google.generativeai`
- `openai`
- `pyaudio`
- `os`
- `time`
- `warnings`
- `faster_whisper`
- `python-dotenv`

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## Acknowledgements

- [OpenAI](https://openai.com/)
- [Google Generative AI](https://ai.google/tools/)
- [Gemini Pro 1 latest](https://example.com/gemini-pro)  <!-- Update this link with the actual one if available -->
- [Faster Whisper](https://github.com/openai/whisper)


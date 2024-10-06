# open_notebooklm_voice_Cloning

This project allows you to create your personalized podcast from a PDF document using AI. It leverages the power of OpenRouter's LLM API and Google Colab to generate a podcast script and then uses text-to-speech to generate the audio podcast.

## Features

*   **Multilingual support:** Generate podcasts in multiple languages, including Arabic.
*   **Audio cloning:** Use your voice or other audio sources to create the podcast.
*   **Open and customizable:** Experiment with the code and add your own features.
*   **Easy to use:** Simply provide a PDF document and your desired audio sources.

## Getting Started

1.  Open the Google Colab notebook provided.
2.  Install the required libraries: `pip install TTS pymupdf`.
3.  Enter your OpenRouter API key in the designated field.
4.  Specify the input PDF document and the audio files you want to use for cloning.
5.  Run the notebook cells to generate the podcast script and audio.
6.  Concatenate the generated audio files to create the final podcast.

## How It Works

1.  The notebook first extracts the text from the input PDF document using `pymupdf`.
2.  It then sends the text to the OpenRouter API with a prompt engineered to generate a podcast script.
3.  The script is parsed, and the dialogue lines are extracted.
4.  Text-to-speech is performed using `TTS` to generate audio for each dialogue line, cloning the voices from the provided audio files.
5.  The audio files are concatenated using a custom function to create the final podcast.

## Future Enhancements

*   Improve the quality of the generated script and audio.
*   Add more features, such as background music and sound effects.
*   Develop a user interface for easier interaction.
*   Explore different LLM models and TTS engines for better performance.

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues to suggest improvements or report bugs.

## Disclaimer

This project is for educational and experimental purposes only. The generated podcasts may not be suitable for commercial use.

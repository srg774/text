# Advanced Text-to-Speech

This is a simple web-based application that uses the browser's built-in speech synthesis API to convert text into speech. The app allows users to customize the pitch, speed, and volume of the generated voice, and choose from various available voices.

## Features

- **Text Input**: Enter any text you want to convert into speech.
- **Voice Selection**: Choose from a list of voices available in your browser.
- **Pitch Adjustment**: Control the pitch of the speech using a slider.
- **Speed Adjustment**: Control the speed (rate) of the speech with a slider.
- **Volume Adjustment**: Control the volume of the speech using a slider.
- **Play Button**: Play the converted speech with your selected settings.

## Live Demo

You can try the application live on GitHub Pages:

[Live Demo](https://srg774.github.io/text/)

## How to Use

1. **Enter Text**: Type the text you want to hear in the "Enter your text here" box.
2. **Select a Voice**: Choose your preferred voice from the dropdown menu.
3. **Adjust Settings**:
   - **Pitch**: Move the slider to change the pitch of the voice.
   - **Speed**: Move the slider to adjust the speech rate (speed).
   - **Volume**: Use the slider to control the volume of the speech.
4. **Play the Voice**: Press the **Play Voice** button to hear the converted speech.

## Requirements

This app uses the **Web Speech API** (specifically, the `SpeechSynthesis` interface) to convert text to speech. As such, it should work in most modern web browsers, including:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge

## Demo

You can try out the application directly in your browser by visiting the link above. The app is hosted on GitHub Pages, so there is no need for installation.

## Limitations

- The list of available voices depends on the browser and the operating system you're using. Some voices may not be available on all platforms.
- Export functionality is not implemented in this version. The app only supports playing the voice directly within the browser.

## Future Improvements

- **Voice Export**: Implement the ability to export speech to audio files (e.g., MP3 or WAV).
- **More Voice Options**: Integrate additional third-party APIs for more voice options.
- **Customization**: Allow users to save their preferences or text input.

## License

This project is open-source and available under the [MIT License](LICENSE).

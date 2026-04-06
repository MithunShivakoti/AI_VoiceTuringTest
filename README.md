# AI Voice Turing Test

A web-based voice analysis demo that listens to a short microphone sample and classifies it as human or robot using browser audio processing.

## Features

- Real-time audio recording with the Web Audio API
- Voice waveform and spectrogram visualization
- Simple heuristic classification based on audio signal features
- Sentiment analysis from transcribed speech text (Chrome/Edge only)
- Responsive dark-themed UI with animated charts

## Files

- `index.html` - the full application, including HTML, styles, and JavaScript logic
- `as.txt` - additional binary file included in the project

## Usage

1. Open a terminal in the project folder:
   ```powershell
   cd C:\Users\mithu\Downloads\voiceturingtest
   ```
2. Start a local server:
   ```powershell
   python -m http.server 8000
   ```
3. Open the app in your browser:
   ```text
   http://localhost:8000
   ```

> Note: The app cannot access your microphone when opened directly via `file://`. Use a local server.

## How to use

1. Click the **Give a shot!** button.
2. Allow microphone access when prompted.
3. Speak naturally for 5 seconds.
4. View the voice analysis results and sentiment feedback.

## Browser requirements

- Modern browser with Web Audio API support
- Chrome or Edge recommended for speech transcription

## Notes

- The classification is heuristic-based and is intended as a demonstration rather than a production-ready voice recognition system.
- If the app shows `No speech transcribed`, try using Chrome or Edge and ensure microphone access is allowed.

## License

This project is open for experimentation and portfolio demonstration.

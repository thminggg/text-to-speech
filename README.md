# Azure Speech To Text

A simple tool to convert text `.txt` to audio `.wav` and captions `.srt` using Microsoft Cognitive Services Speech SDK.

## Usage

1. Install dependencies

```bash
yarn install
```

2. Create a `.env` file with the following environment variables:

```bash
SPEECH_KEY=your-speech-key
SPEECH_REGION=your-speech-region
VOICE_NAME=your-voice-name
OUTPUT_DIR=your-output-directory
```

3. Run the app

```bash
# To generate audio
yarn start

# To generate captions
yarn caption --audio ./speech/2024-9-10-23-24-47.wav --captionDir ./captions --srt
```

## License

MIT

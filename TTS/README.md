# TTS Multi-Mode

A modern web application for text-to-speech using the Web Speech API with dual operating modes.

## 🚀 Try it Live

**[Launch TTS Multi-Mode →](https://harold-mitts.github.io/TTS/tts-reader.html)**

No installation required - runs directly in your browser.

## Features

- 🎙️ **Dual Modes**: Switch between Single Voice and Conversation modes
- 💬 **Conversation Mode**: Alternating dual-voice dialog with "A:" and "B:" prefixes
- 🗣️ **Single Voice Mode**: Standard text-to-speech for any content
- 🎨 **Modern UI**: Dark theme with glassmorphism effects and responsive design
- 🎚️ **Voice Controls**: Adjustable rate, pitch, and volume for each mode
- 🔊 **Smart Voice Selection**: Auto-selects Microsoft Andrew and Jenny voices
- 📚 **Long Text Support**: Intelligent chunking (4000 chars) to prevent browser timeouts
- 🔄 **Smooth Transitions**: Seamless queueing in conversation mode for natural dialog flow
- ⏯️ **Playback Controls**: Play, pause, and stop controls
- 📦 **All-in-One**: Single HTML file with embedded CSS and JavaScript for easy deployment

## Usage

### Single Voice Mode
1. Open `tts-reader.html` in a modern web browser
2. Ensure "Single Voice" mode is selected (default)
3. Enter any text in the text area
4. Adjust voice parameters using the sliders
5. Click "Play" to hear the text spoken

### Conversation Mode
1. Click the "Conversation" mode button
2. Format your text with speaker labels:
   ```
   A: Hello! How are you today?
   B: I'm doing great, thanks for asking!
   A: That's wonderful to hear.
   ```
3. Voice A and Voice B will automatically alternate
4. Adjust shared rate, pitch, and volume settings
5. Click "Play" to hear the conversation

## Technical Details

- **HTML**: Semantic structure with accessibility in mind
- **CSS**: Modern dark theme with radial gradients and glassmorphism effects (embedded)
- **JavaScript**: ES6+ class-based architecture with Web Speech API integration (embedded)
- **Browser Support**: Works in modern browsers that support the Web Speech API
- **Architecture**: Single self-contained HTML file with all assets embedded for portability
- **Dialog Parsing**: Supports both "A:" and "[A]" formats for conversation mode

## Files

- `tts-reader.html` - Complete application with embedded CSS and JavaScript

## License

See LICENSE file for details.

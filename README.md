# CommandBot 🤖

A Python-based rule-based chatbot with voice and text interaction capabilities, featuring games, web integrations, and utility commands.

## ✨ Features

- **Voice & Text Input**: Switch between voice and text interaction modes
- **Built-in Games**: Play Tic Tac Toe and Number Guessing games
- **Web Integrations**: Open YouTube, Google, Facebook, WhatsApp, Gmail
- **Utility Functions**: Calculator, calendar display, time/date queries
- **Entertainment**: Jokes, riddles, and fun facts
- **System Integration**: Launch Spotify, Notepad, and other applications
- **Text-to-Speech**: Audio responses for better user experience

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- Microphone (for voice input)
- Internet connection (for voice recognition and web features)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/udaykumar0515/CommandBot.git
cd CommandBot
```

2. Install required dependencies:
```bash
pip install pyttsx3==2.90 speechrecognition==3.8.1 pywhatkit==5.4
```

3. Run the chatbot:
```bash
python CommandBot.py
```

## 🎮 Usage

### Basic Commands

- **Greeting**: Say "hi" or "hello"
- **Voice Mode**: Type "voice chat" to switch to voice input
- **Text Mode**: Type "text" to switch to text input
- **Help**: Type "help" to see all available commands

### Game Commands

- **Play Games**: Type "game mode" or "play game"
- **Available Games**: Tic Tac Toe, Number Guessing

### Utility Commands

- **Time**: "time now" or "time"
- **Date**: "today date" or "date today"
- **Calculator**: "calculate [expression]" (e.g., "calculate 2+2")
- **Calendar**: "calendar"

### Web Commands

- **YouTube**: "open youtube" or "play [song name]"
- **Google Search**: "search [query]"
- **Social Media**: "open facebook", "open whatsapp"
- **Email**: "open mail"
- **Weather**: "current weather"

### Entertainment

- **Jokes**: "tell me a joke"
- **Riddles**: "tell me a riddle"
- **Fun Facts**: "tell me a fun fact"

### System Commands

- **Spotify**: "spotify"
- **Notepad**: "notepad"
- **Exit**: "exit"

## 🛠️ Technical Details

### Dependencies

- `pyttsx3`: Text-to-speech engine
- `speechrecognition`: Voice input processing
- `pywhatkit`: YouTube and WhatsApp integration
- `webbrowser`: Web page opening
- `subprocess`: System application launching

### Architecture

The chatbot uses a rule-based system with predefined responses and command handlers. It processes user input through pattern matching and executes corresponding functions.

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Created by [udaykumar0515](https://github.com/udaykumar0515)

## 🎯 Future Enhancements

- [ ] Add more games
- [ ] Implement conversation memory
- [ ] Add more web integrations
- [ ] Improve voice recognition accuracy
- [ ] Add configuration file support
- [ ] Implement plugin system

---

**Note**: This is a rule-based chatbot, not an AI-powered system. It uses predefined responses and command patterns to interact with users.

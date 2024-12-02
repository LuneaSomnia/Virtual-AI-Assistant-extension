# Voice-AI-Assistant-extension
A chrome extension that utilizes chrome's built-in AI models to help user surf the web and basically functions like a virtual assistant but solely on chrome.
1. Key Files Analysis:
-manifest.json confirms it's a Chrome extension
-Uses HTML/CSS/JavaScript for the interface
-Background scripts handle core functionality
-Content scripts manage webpage interactions
2. Core Breakdown: Features:
-Voice command recognition
-AI-powered responses
-Browser control through voice
-Text-to-speech output
-Custom wake word detection
-Multiple language support

Technologies:

-WebSpeech API for voice recognition
-OpenAI API for AI processing
-Chrome Extension APIs
-WebAudio API for audio processing
3. Technical Insights:
-Modular code structure separating concerns
-Real-time audio processing
-Event-driven architecture
-Secure API handling
-Browser storage for settings
4. Implementation Details: Entry Points:
-popup.html for user interface
-background.js for core processing
-content.js for webpage interaction

Configuration:

-Customizable wake words
-Adjustable voice settings
-API key configuration
-Language preferences

Project Purpose: This extension transforms browser interaction through voice commands, making web browsing accessible and hands-free. It combines AI capabilities with voice recognition for a smart browsing experience.

To use this extension:

-Clone the repository
-Add your OpenAI API key
-Load as unpacked extension
-Configure voice settings
-Start using voice commands

The project effectively merges voice technology with AI to create an intuitive browser assistant, suitable for both accessibility needs and convenience.

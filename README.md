This project is a Text to Speech (TTS) Converter built using JavaScript Speech Synthesis API.
It allows users to enter text, select male or female voice, convert text into speech, and stop the speech at any time.

**Features**

Convert text into speech
Select male or female voice
Start and stop speech anytime
Simple and user-friendly interface
Uses built-in browser Speech Synthesis API
No external libraries required

**How It Works**
User enters text in the input area
Available voices are loaded using speechSynthesis.getVoices()
User selects male or female voice
On clicking Speak, the text is converted to speech
Stop button cancels the ongoing speech using speechSynthesis.cancel()
User selects speed and pitch also

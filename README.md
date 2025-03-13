# MultiLingual-Voice-Chatbot
**Overview**
This project is a multilingual chatbot that can process and respond to voice inputs in multiple languages. It leverages speech recognition, language detection, translation, and a conversational AI model to provide seamless interactions in various languages.


**Features**
Speech Recognition: Converts audio input to text using Google's Speech Recognition API.
Language Detection: Identifies the language spoken using langid.
Translation: Translates non-English text to English and vice versa using googletrans.
Conversational AI: Uses Microsoft's DialoGPT to generate chatbot responses.
Text-to-Speech: Converts chatbot responses back to speech using gTTS.

**Steps:**
The user provides an audio input.
The language is detected.
Speech is converted to text.
The text is translated into English (if necessary).
The chatbot generates a response.
The response is translated back to the original language.
The response is converted to speech and played back.
The user can continue or exit.

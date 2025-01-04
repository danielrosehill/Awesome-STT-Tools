# Awesome Speech To Text (STT) Tools

A small compilation of tools that I have found helpful for speech to text (STT), including browser extensions, desktop applications, cloud-based APIs, and ASR libraries. Many of these are automatic speech recognition (ASR) tools leveraging AI models.

## Browser Extensions (Google Chrome)

### VoiceIn

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Download-brightgreen?logo=google-chrome)](https://chromewebstore.google.com/detail/voice-in-speech-to-text-d/pjnefijmagpd)

- Popular speech-to-text dictation tool for Chrome.
- Utilizes the Chrome browser API for transcription.
- Offers a lifetime deal for heavy users.
- Well-developed and user-friendly interface.

### Whisper AI

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Download-brightgreen?logo=google-chrome)](https://chromewebstore.google.com/detail/whisperai-ai-driven-speec/klhcnkknganbneegjihbcfjoifiomhfn?hl=en)
![Model](https://img.shields.io/badge/Model-OpenAI_Whisper-blue)
![License](https://img.shields.io/badge/License-Commercial-orange)

- AI-driven speech-to-text Chrome extension.
- Utilizes OpenAI's Whisper model for transcription.
- Offers excellent accuracy and good pricing plans.
- Regularly updated with new features.

### Whispering

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Download-brightgreen?logo=google-chrome)](https://chromewebstore.google.com/detail/whispering/oilbfihknpdbpfkcncojikmooipnlglo?hl=en)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/braden-w/whispering-extension)
![Model](https://img.shields.io/badge/Model-OpenAI_Whisper-blue)

- Chrome extension for self-hosted OpenAI Whisper.
- Allows users to provide their own OpenAI API key.
- Pay-as-you-go transcription service.
- Project seems inactive, marked as archived on GitHub.

### Echo STT

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Download-brightgreen?logo=google-chrome)](https://chromewebstore.google.com/detail/echo-speech-to-text-dicta/dogdmonghloddlmlbdpchiedlckadgal?hl=en)
[![Website](https://img.shields.io/badge/Website-Visit-blue?logo=google-chrome)](https://www.echo-stt.com/)

- Privacy-focused speech-to-text Chrome extension.
- Emphasizes user data privacy, no storage on servers.
- Provides accurate transcription without compromising user data.

### Speech to Text Anywhere

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Download-brightgreen?logo=google-chrome)](https://chromewebstore.google.com/detail/speech-to-text-anywhere-v/kpgkkdghpdjgpccfkbkpdncpgcjdjmjg?hl=en)

- Versatile speech-to-text extension for Chrome.
- Supports multiple languages and dialects.
- Allows for text insertion in any text field on any website.
- Simple and easy-to-use interface.

### Dictation Box

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Download-brightgreen?logo=google-chrome)](https://chromewebstore.google.com/detail/dictation-box-speech-to-t/kmlclgbfnlbgmghhifacghcfcdgdhfge?hl=en)

- Simple, in-browser dictation Chrome extension.
- Features a convenient, resizable text box.
- Leverages the browser's speech-to-text API for transcription.
- Focuses on ease of use and quick dictation.

## Desktop Applications (Linux)

### Nerd Dictation

![Stars](https://img.shields.io/github/stars/ideasman42/nerd-dictation?style=social)
![License](https://img.shields.io/github/license/ideasman42/nerd-dictation?color=green)

- Linux command-line tool for offline speech-to-text.
- VOSK API.
- Allows text entry into any typed field via key bindings.

### Speech Note

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![GitHub](https://img.shields.io/github/stars/mkiol/dsnote?style=social)

- Linux desktop notepad application.
- Utilizes locally hosted Whisper models for speech-to-text.
- Text entry is limited to the app's interface.

### Simon

![Language](https://img.shields.io/badge/Language-C%2B%2B-blue?logo=cplusplus)
![License](https://img.shields.io/badge/License-GPLv3-green)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/Simon-ASR/simon)

- Open-source speech recognition program for Linux.
- Highly customizable and adaptable to different uses.
- Built on top of Kaldi ASR toolkit, uses CMU Sphinx models.
- Requires setting up speech models, offers extensive configuration options.

### DeepSpeech

![Python](https://img.shields.io/badge/Python-3.7+-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MPL_2.0-green)
![GitHub](https://img.shields.io/github/stars/mozilla/DeepSpeech?style=social)

- Mozilla’s open-source, pre-trained speech-to-text engine.
- Can be run locally or in the cloud.
- Requires an understanding of Python and some expertise in ML.
- Offers good accuracy and flexibility.

## Desktop Applications (Windows)

### Windows Speech Recognition

![Windows](https://img.shields.io/badge/OS-Windows-blue?logo=windows)

- Built-in speech recognition tool in Windows OS.
- Allows voice control of the computer and dictation.
- Requires initial setup and training for best accuracy.
- Basic and not as powerful as newer AI-based solutions.

### Otter.ai (Desktop App)

[![Website](https://img.shields.io/badge/Website-Visit-blue?logo=google-chrome)](https://otter.ai/)
![License](https://img.shields.io/badge/License-Commercial-orange)

- AI-powered transcription and note-taking application for Windows.
- Excellent accuracy and supports multiple speakers.
- Cloud-based with a desktop app for real-time transcription.
- Focuses on meeting transcription.

### Dictanote

[![Website](https://img.shields.io/badge/Website-Visit-blue?logo=google-chrome)](https://dictanote.co/)
![License](https://img.shields.io/badge/License-Commercial-orange)

- Windows desktop app for voice dictation and transcription.
- Supports multiple languages and can integrate with text editors.
- Uses cloud-based STT for processing.
- Offers a free tier and premium plans.

## Desktop Applications (macOS)

### Dictation (macOS)

![macOS](https://img.shields.io/badge/OS-macOS-blue?logo=apple)

- Built-in dictation feature in macOS.
- Can be activated with keyboard shortcuts or Siri.
- Works with most applications for text input.
- Uses Apple's speech recognition services.

### Descript

[![Website](https://img.shields.io/badge/Website-Visit-blue?logo=google-chrome)](https://www.descript.com/)
![License](https://img.shields.io/badge/License-Commercial-orange)

- AI-powered audio/video editing with powerful transcription.
- Desktop app for macOS, focuses on transcript-based editing.
- Offers high-accuracy and speaker identification.
- Popular among podcasters and video editors.

### Trint

[![Website](https://img.shields.io/badge/Website-Visit-blue?logo=google-chrome)](https://trint.com/)
![License](https://img.shields.io/badge/License-Commercial-orange)

- Transcription and collaboration platform for macOS.
- Useful for teams, allows reviewing and correcting transcripts.
- Offers integrations and workflows for media production.
- Cloud-based with Mac client.

## Cloud-Based APIs

### Google Cloud Speech-to-Text

![Cloud](https://img.shields.io/badge/Cloud-Google_Cloud-blue?logo=googlecloud)
![License](https://img.shields.io/badge/License-Commercial-orange)
![Model](https://img.shields.io/badge/Model-Various-blue)

- Powerful and accurate speech-to-text API.
- Supports many languages and customization.
- Offers real-time and batch transcription capabilities.
- Widely used in enterprise and development environments.

### Amazon Transcribe

![Cloud](https://img.shields.io/badge/Cloud-Amazon_AWS-blue?logo=amazonaws)
![License](https://img.shields.io/badge/License-Commercial-orange)
![Model](https://img.shields.io/badge/Model-Various-blue)

- Scalable and reliable speech-to-text API from AWS.
- Includes features like speaker diarization and custom vocabularies.
- Used extensively for media transcription and call center analytics.
- Well-documented for integration with other services.

### Microsoft Azure Speech to Text

![Cloud](https://img.shields.io/badge/Cloud-Microsoft_Azure-blue?logo=microsoftazure)
![License](https://img.shields.io/badge/License-Commercial-orange)
![Model](https://img.shields.io/badge/Model-Various-blue)

- Robust cloud-based speech-to-text API from Azure.
- Supports real-time and batch processing.
- Provides high-accuracy speech recognition, including customized options.
- Suited to enterprise applications.

### AssemblyAI

[![Website](https://img.shields.io/badge/Website-Visit-blue?logo=google-chrome)](https://www.assemblyai.com/)
![License](https://img.shields.io/badge/License-Commercial-orange)
![Model](https://img.shields.io/badge/Model-Proprietary-blue)

- AI-powered speech-to-text API.
- Emphasis on speed and accuracy for developers.
- Offers additional features like sentiment analysis.
- Focuses on developer ease-of-use.

## ASR Libraries and Frameworks

### Kaldi

![Language](https://img.shields.io/badge/Language-C%2B%2B-blue?logo=cplusplus)
![License](https://img.shields.io/badge/License-Apache_2.0-green)
![GitHub](https://img.shields.io/github/stars/kaldi-asr/kaldi?style=social)

- Powerful toolkit for speech recognition research.
- Primarily used for developing and implementing ASR models.
- Open source, but has a steep learning curve.
- Highly extensible and customizable.

### VOSK

![Language](https://img.shields.io/badge/Language-Python/C%2B%2B-blue?logo=python)
![License](https://img.shields.io/badge/License-Apache_2.0-green)
![GitHub](https://img.shields.io/github/stars/alphacep/vosk-api?style=social)
![Model](https://img.shields.io/badge/Model-Various-blue)

- Lightweight and offline-capable ASR library.
- Supports many languages with pre-trained models.
- Good for embedding STT capabilities into desktop applications.
- Provides Python, C++, and other language bindings.

### SpeechBrain

![Python](https://img.shields.io/badge/Python-3.7+-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-Apache_2.0-green)
![GitHub](https://img.shields.io/github/stars/speechbrain/speechbrain?style=social)

- Open-source toolkit for developing speech applications.
- Can be used to train and deploy customized ASR models.
- Flexible and well-documented.
- Used in many academic and research projects.

 ## Mobile Applications (Android)

### Google Live Transcribe

![Android](https://img.shields.io/badge/OS-Android-blue?logo=android)
![License](https://img.shields.io/badge/License-Free-green)

- Accessibility app for Android.
- Provides real-time transcription of speech.
- Supports multiple languages and can save transcripts.
- Integrates well with the Android ecosystem.

### Otter.ai (Mobile App)

[![Website](https://img.shields.io/badge/Website-Visit-blue?logo=google-chrome)](https://otter.ai/)
![License](https://img.shields.io/badge/License-Commercial-orange)
- AI-powered transcription and note-taking application for Android.
- Excellent accuracy and supports multiple speakers.
- Cloud-based with a mobile app for real-time transcription.
- Focuses on meeting transcription.

### Speech To Text App

[![Google Play Store](https://img.shields.io/badge/Google_Play_Store-Download-brightgreen?logo=google-play)](https://play.google.com/store/apps/details?id=com.speechtotext.voicenotes.speechtotext)
![License](https://img.shields.io/badge/License-Free-green)

- Simple and free speech to text application for Android.
- Supports multiple languages.
- Allows for sharing transcribed text via various methods.

### Just Press Record

[![Google Play Store](https://img.shields.io/badge/Google_Play_Store-Download-brightgreen?logo=google-play)](https://play.google.com/store/apps/details?id=com.openplanet.justpressrecord)
![License](https://img.shields.io/badge/License-Commercial-orange)

- Mobile transcription app for Android.
- Focuses on quick and easy voice recording and transcription.
- Supports multiple file formats for audio.
- Offers cloud backup for transcriptions.

## Mobile Applications (iOS)

### Apple Dictation (iOS)

![iOS](https://img.shields.io/badge/OS-iOS-blue?logo=apple)

- Built-in dictation feature in iOS.
- Can be activated with keyboard shortcuts or Siri.
- Works within most applications for text input.
- Uses Apple's speech recognition services.

### Otter.ai (Mobile App)

[![Website](https://img.shields.io/badge/Website-Visit-blue?logo=google-chrome)](https://otter.ai/)
![License](https://img.shields.io/badge/License-Commercial-orange)

- AI-powered transcription and note-taking application for iOS.
- Excellent accuracy and supports multiple speakers.
- Cloud-based with a mobile app for real-time transcription.
- Focuses on meeting transcription.

### Just Press Record

[![App Store](https://img.shields.io/badge/App_Store-Download-brightgreen?logo=apple)](https://apps.apple.com/us/app/just-press-record/id1033347686)
![License](https://img.shields.io/badge/License-Commercial-orange)

- Mobile transcription app for iOS.
- Focuses on quick and easy voice recording and transcription.
- Integrates with other apps, like Apple's Shortcuts.
- Offers iCloud sync for transcriptions.

### Transcribe - Speech to Text

[![App Store](https://img.shields.io/badge/App_Store-Download-brightgreen?logo=apple)](https://apps.apple.com/us/app/transcribe-speech-to-text/id1450613898)
![License](https://img.shields.io/badge/License-Free/Paid-green)

- iOS app for real-time speech-to-text.
- Supports multiple languages.
- Offers features like exporting transcriptions and adding timestamps.
- Free with in-app purchases for additional features.

---

## Use Case Statement

## Author

Daniel Rosehill
(public at danielrosehill dot com)

## Licensing

This repository is licensed under CC-BY-4.0 (Attribution 4.0 International)
[License](https://creativecommons.org/licenses/by/4.0/)

### Summary of the License
The Creative Commons Attribution 4.0 International (CC BY 4.0) license allows others to:
- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the license terms.

#### License Terms
- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **No additional restrictions**: You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

For the full legal code, please visit the [Creative Commons website](https://creativecommons.org/licenses/by/4.0/legalcode).
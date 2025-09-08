# MIKE - Voice Assistant
MIKE, is a voice assistant built with an ESP32, featuring Google cloud services, Perplexity AI Intelligence and Spotify music controls.

## About MIKE
**Wake Word Activation**: Saying the word "MIKE" activates the assistant. It uses advanced speech recognition to detect your voice and respond with high accuracy.

**Spotify Music Control**: You can play, pause, skip songs and essentially, have full control over your Spotify experience using MIKE. You can also search for tracks, artists and playlists using voice commands.

**Examples:** 
> MIKE, play the latest Linkin Park release.

> MIKE, play some liminal music.

> MIKE, start the playlist, "Japan Peace".

**Perplexity AI Intellgence**: MIKE is powered by Perplexity's Sonar API for having intelligent conversations, real-time web search, and accurate answers to your questions. 

**High Quality Speech**:
Google Cloud Text-to-Speech with British accent provides natural, clear voice responses that sound professional and engaging. 

**Wi-Fi Setup Portal**: Connect to the MIKE-Setup network and configure your Wi-Fi credentials through a web interface.

**Low Power Design**: MIKE has an efficient ESP32 architecture with built-in DAC for audio output and optimized power consumption for continuous operation and maintenance.

## What MIKE can do
MIKE is your intelligent AI companion that responds to voice commands, controls music, answers questions, and provides accurate information in real time. You just have to say "MIKE" followed by your request.

**A few examples:**

> You: "MIKE, play some jazz music"
>
> **MIKE**: "Searching for jazz music on Spotify. Now playing smooth jazz playlist on your speaker."


> You: "MIKE, what's the weather like today?"
>
> **MIKE**: "Today in your area, it's partly cloudy with a high of 28°C and a low of 22°C. Perfect weather for outdoor activities."


> You: "MIKE, pause the music"
>
> **MIKE**: "Music paused. Would you like me to resume it later?"

> You: "MIKE, tell me about quantum physics"
>
>  **MIKE**: "Quantum physics is the study of matter and energy at the smallest scales. It reveals how particles behave in ways that seem impossible in our everyday world..."


> You: "MIKE, skip this song"
>
> **MIKE**: "Skipping to the next track. Now playing a different selection for you."


> You: "MIKE, what's happening in the news?"
>
> **MIKE**: "Here are today's top headlines: Technology sector sees growth, climate summit reaches agreement, and space exploration advances continue..."


## Technical Specifications

  **Microcontroller**: ESP32 DevKit V1
  
  **Wake Word**: "MIKE" (customizable)
  
  **Speech Recognition**: Assembly AI Speech-to-Text
 
  **Text-to-Speech**: VOICE RSS Text-To-Speech (British Voice)
 
  **AI Engine**: Perplexity Sonar Pro API
 
  **Music Service**: Spotify Web API
 
  **Audio Input**: KY-037 High Sensitivity Microphone
 
  **Audio Output**: PAM8403 Amplifier + Speaker
 
  **Power Supply**: 5V USB or External 7-12V
 
  **Connectivity**: Wi-Fi 802.11 b/g/n

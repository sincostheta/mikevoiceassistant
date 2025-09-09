# MIKE - Voice Assistant
MIKE is an open source AI Voice Assistant and Smart Speaker built using an ESP-32, featuring Perplexity AI Intelligence and Spotify Music Controls.

**WIP**

**What's left:**

Materials used [GET EXACT PRICES] {AYE AYE CAPTAIN}

Finishing the full project

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

## How to Set Up Mike
   - Turn MIKE on and wait for 30 seconds
   - Go to the WIFI Menu of your mobile and connect to `MIKE-Setup` with the password `mike123`
   - It should open a website in your browser, if it doesn't open automatically, go to `192.168.4.1` from your preferred web browser
   - Enter your wifi name and the wifi password to the given blanks in the website and submit the form
   - Wait for about a minute to initialize and start using!

## How to use MIKE properly
   - Use the wake word "MIKE" for it to respond to you (can be customized)
   - Speak clearly and at a normal pace for better recognition
   - Wait for the blue LED to light up before issuing a command
   - Keep MIKE within 1 metre radius for optimal voice pickup
   - Keep MIKE in quiet environments with minimal background noise

## Technical Specifications

  | Device | Model |
  | --- | --- |
  | Microcontroller | ESP32 DevKit V1 |
  | Speech Recognition | Assembly AI Speech-to-Text |
  | Text-to-Speech | Voice RSS Text-to-Speech (British Voice)
  | AI Engine | Perplexity Pro Sonar API |
  | Music Service | Spotify Web API
  | Audio Input | KY-037 High Sensitivity Microphone |
  | Audio Output | PAM8403 Amplifier + Speaker |
  | Power Supply | 5V USB or External 7-12V |
  | Connectivity | Wi-Fi 802.11 b/g/n |
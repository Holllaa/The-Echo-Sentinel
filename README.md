# The-Echo-Sentinel
Imagine having an intuitive system installed on my laptop that acts as a dedicated voice assistant. This setup empowers me to interact with my laptop using natural language commands. For instance, I can effortlessly instruct it to initiate tasks like launching Spotify for music, accessing games for entertainment or even pulling up YouTube etc.
This Python script implements a voice-controlled assistant using pyautogui and speech_recognition. It's designed to execute various actions based on voice commands:

"Jarvis play": Opens YouTube, plays the first video, and searches for a specified query if included in the command.
"I am bored Jarvis": Launches the Valorant game for entertainment.
"Jarvis run": Opens Spotify and potentially executes further actions based on a secondary command within the initial voice input.
"Jarvis self destruct": Initiates a shutdown process by navigating through the Windows menu.
When unrecognized commands are spoken, the assistant defaults to initiating a search query using ChatGPT on the web. The assistant interacts with the system by emulating mouse clicks and keyboard inputs, triggered by specific recognized voice commands.

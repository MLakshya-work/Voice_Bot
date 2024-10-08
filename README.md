**Installation Instructions**

To get started with this project, install the necessary Python libraries and dependencies:
  
  1) brew install portauido 
  2) pip install "assemblyai[extras]"
  3) pip install elevenlabs==0.3.0b0
  4) brew install mpv
  5) pip install --upgrade openai


**API KEYS**

This project requires API keys from the following services:

AssemblyAI: https://www.assemblyai.com/

OpenAI: https://help.openai.com/en/articles/4936850-where-do-i-find-my-openai-api-key

ElevenLabs: https://elevenlabs.io/


**IMPORTANT NOTE:**

1) You must create your own API keys for all three services and add them in the appropriate places in the code.

2) If you wish to use a different voice for audio generation, replace "Jessica" with the desired voice name at Step 4: Generate audio with ElevenLabs:

      audio_stream = generate(
          api_key = self.elevenlabs_api_key,
          text = text,
          voice = "**Jessica**", # Replace with the name of your preferred voice
          stream = True )

3) AssemblyAI features now require a subscription, and the functionality will not work without a paid plan.







  

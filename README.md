# VoiceCloningAI

  This Voice Cloning AI module enables the user to create the artificial simulation of a persons voice. 
  
  Dependencies:
  
 * Mendix Modeler - 9.18.4
 * Play Audio - https://marketplace.mendix.com/link/component/120804
 * API Key - https://beta.elevenlabs.io/voice-lab
  
  Configuration:
  
 * Create a account on Elevenlabs to access the API's and API key - https://api.elevenlabs.io/docs#/
 * Get the API key from Profile section - https://beta.elevenlabs.io/voice-lab
 * Add the Voice Cloning Overview page
 * Inside the data view, add the reference selector and description text area
 * Call the DS_OpenVoice microflow in the dataview
 * Once application is ran, select any one of the voice in the VoiceCloning_Overview page 
 * Enter the description which need's to get cloned with the selected voice
 * Click on the Play button to generate the cloned voice
 
 Screenshots:
 
 <img width="227" alt="Flows" src="https://user-images.githubusercontent.com/47358611/221792098-67e68f77-6497-4507-a604-22d6d24d6aca.PNG">
 <img width="868" alt="DS_OpenVoice" src="https://user-images.githubusercontent.com/47358611/221792046-2c338e7e-dab8-4b8d-977d-51b6144bb909.PNG">
<img width="480" alt="PlayAudio" src="https://user-images.githubusercontent.com/47358611/221792127-400bad29-eea7-4736-b4e1-d05867fb363f.PNG">
<img width="910" alt="UI" src="https://user-images.githubusercontent.com/47358611/221792150-c3a2cb9f-e6df-439d-9d81-19ed92072dd7.PNG">

# AUDIRE-Cohort of Data ( Image Analysis )

"AUDIRE : COHORT OF DATA" is a multi-modal AI application that integrates advanced image and speech processing technologies. It aims to provide a seamless interface for users to interact with images using voice commands, and to receive detailed image descriptions and responses in both text and audio formats. By leveraging state-of-the-art models from Hugging Face's transformers and OpenAI's Whisper, this project showcases the potential of AI in enhancing human-computer interactions through natural language and visual understanding.
 
## Features
 
1. **Multi Input Format**:
   - Image Input: Users can upload an image, which is then processed by an image-to-text pipeline using the LLaVA model. 
   - Audio Input: Users can provide voice input via a microphone. The Whisper model from OpenAI transcribes the spoken words into text. This text is then used as a prompt for the image analysis, creating an interactive experience where users can ask questions about the 
     image.
 
2. **Image Analysis**:
   - The model is prompted with detailed instructions to provide in-depth analyses, ensuring that the generated descriptions are rich in detail and accuracy.
   - The model detects the language of the audio input, ensuring accurate transcription
    
 
3. **Multi Output Format **:
   - Text Output : The model is to provide the  description of image in and summarizes the text within 200 words to diplay in front of user.
   -  Audio Output :The detailed image description or the response to the user's query is converted back into speech.
 
4. **Interactive UI**:
   - The project uses Gradio to create a user-friendly interface where users can easily upload images and provide voice input. The interface displays the transcribed text, the AI's detailed response, and the audio response, providing a comprehensive interaction 
     experience.
 
## Technologies Used
  
- *HuggingFace Modal*
- *Quantization*
- *Gradio*
- *Python*
- *Whisper*
- *NLTK*
- *Google GTTS*
  




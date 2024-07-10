# AUDIRE-Cohort of Data ( Image Analysis )

Abstract
The project "AUDIRE : COHORT OF DATA" is a multi-modal AI application that integrates advanced image and speech processing technologies. It aims to provide a seamless interface for users to interact with images using voice commands, and to receive detailed image descriptions and responses in both text and audio formats. By leveraging state-of-the-art models from Hugging Face's transformers and OpenAI's Whisper, this project showcases the potential of AI in enhancing human-computer interactions through natural language and visual understanding.

Functionality
Image Description and Analysis:

Image Input: Users can upload an image, which is then processed by an image-to-text pipeline using the LLaVA model. 
The model generates a detailed description of the image, highlighting its characteristics and answering specific queries about it.

Detailed Prompts: The model is prompted with detailed instructions to provide in-depth analyses, ensuring that the generated descriptions are rich in detail and accuracy.
Speech-to-Text Transcription 

Audio Input: Users can provide voice input via a microphone. The Whisper model from OpenAI transcribes the spoken words into text. This text is then used as a prompt for the image analysis, creating an interactive experience where users can ask questions about the image.
Language Detection: The model detects the language of the audio input, ensuring accurate transcription.
Text-to-Speech Conversion:

Response Generation: The detailed image description or the response to the user's query is converted back into speech using Google Text-to-Speech (gTTS). This allows users to hear the AI's response, making the interaction more natural and accessible.
Interface Design:

Gradio Interface: The project uses Gradio to create a user-friendly interface where users can easily upload images and provide voice input. The interface displays the transcribed text, the AI's detailed response, and the audio response, providing a comprehensive interaction experience.

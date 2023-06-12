# Speech_to_Image_Capstone_Project

# Speech to Art using AI

Speech to Art using AI is an innovative project that aims to inspire and assist artists by transforming spoken ideas into unique, generated pieces of art. Utilizing deep learning technologies, this system employs speech recognition and text-to-image generation to create art from verbal prompts. This tool is user-friendly and intuitive, making it ideal for artists seeking fresh perspectives and inspiration.

<img width="389" alt="Screen Shot 2023-06-12 at 12 28 35" src="https://github.com/omniaelmenshawy/Speech_to_Image_Capstone_Project/assets/77496383/58f51d61-423a-4f9c-94c4-99e8cd9b9a9c">


_Image 1: User Interface asking the user to start recording_


## Project Details

This project leverages two core deep learning methodologies:

- **Speech Recognition:** We use a speech recognition library that allows the user to provide input via voice. The program listens for five seconds, adjusting for ambient noise to focus on capturing the user's voice clearly. After capturing the input, it converts the speech into text.

- **Text-to-Image Generation:** Once the speech is converted into text, it is passed to a Hugging Face model - specifically, the Stable Diffusion 2.1 model. This model converts the text into a corresponding image.

<img width="1174" alt="Screen Shot 2023-06-12 at 12 25 20" src="https://github.com/omniaelmenshawy/Speech_to_Image_Capstone_Project/assets/77496383/21e70612-5c60-4f77-afe8-6f2403069325">

_Image 2: Example of generated art from verbal prompt_

This project was implemented in Python using tkinter for GUI creation, the SpeechRecognition library for audio processing, the Hugging Face model for text-to-image conversion, and the PIL library for image handling.

## Prerequisites

To run this program, you will need to install the following Python libraries:

- tkinter
- speech_recognition
- requests
- PIL

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install these libraries.

```bash
pip install tkinter
pip install SpeechRecognition
pip install requests
pip install pillow
```

## Usage

1. Clone this repository:
```bash
git clone https://github.com/omniaelmenshawy/Speech-to-Art-using-AI.git
```

2. Navigate to the project directory:
```bash
cd Speech_to_Image_Capstone_Project
```

3. Run the script:
```bash
python main.py
```

4. Click the "Start Recording" button and speak your prompt within the given 5 seconds.

5. Wait for the application to process and generate your unique piece of art.

## Final Remarks and Acknowledgments

This project was designed to offer a new perspective for artists and assist in idea generation. While the current implementation listens for five seconds and uses a specific Hugging Face model, the setup can be customized as per the user's preferences.

We would like to express our gratitude to our advisor, Prof. Fatih Kahraman, for his valuable insights and relentless support throughout the duration of this project.

Please note that the use of the Hugging Face API and Stable Diffusion 2.1 model requires a valid API key. You can generate your own key by creating a free account on the [Hugging Face website](https://huggingface.co/join).

- Special thanks for my project teammates, Qatrelnada Almarzoq and Hashem Alshami.

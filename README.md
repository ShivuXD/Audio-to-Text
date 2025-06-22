# Audio-to-Text

This Python script is made on Google colab to convert an audio file ( .mp3 ) to display it's information in text. This program uses SpeechRecognition and, AudioSegment in order to extract the dialogues/speeches and, write them as a text.

## Requirements

- Python 3.x
- `SpeechRecognition` library
- `pydub` library
- A .mp3 file of your choice

- ## Utilization

 1. **Clone this repository.**

 2. **Google Colab. (Optional)**  

    Click on the `Audio-To-Text.ipynb` and, then proceed to click on " Open in Colab ". The python script will open in Google Colab where you can run this program.
  
  3. **Prepare a .mp3 file.**

       Install/Create a .mp3 file.
     *Note* : The .mp3 must be clear in voice/speeches and, should NOT have any kind of noise or, unclarity. The program would show error if the uploaded file contains any kind of noise/unclarity.

  4. **Upload the .mp3 file.**
 
  5. **Execute.**

     Run the last cell of the program and, wait for sometime. The program will take few seconds or, minute depending upon the length of the .mp3 file.

  7. **Confirm.**

     The extracted speech from the file will appear as the text at the bottom of the code cell.


  ### Speech Extraction ###

  This python script uses `pydub` library for audio processing and, `SpeechRecognition` for the speech extraction from the .mp3 file and, conversion of it to text as the end result.

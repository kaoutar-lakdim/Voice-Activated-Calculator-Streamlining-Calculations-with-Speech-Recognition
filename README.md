
![my-Voice-Activated Calculator_ Streamlining Calculations with Speech Recognition-4](https://github.com/Yassine-Squalli-Houssaini/Voice-Activated-Calculator-Streamlining-Calculations-with-Speech-Recognition/assets/127676452/af73ea57-e424-4e79-afc7-252d287d5a73)


  
The Voice-Activated Calculator is a Python program that leverages the power of speech recognition to perform arithmetic calculations based on spoken digits and operations. This innovative calculator eliminates the need for manual input and allows users to simply speak their calculations, making mathematical tasks more convenient and accessible.

## Introduction

Calculators have been essential tools for performing mathematical operations quickly and accurately. However, traditional calculators often require manual input, which can be time-consuming and prone to errors. The Voice-Activated Calculator aims to overcome these limitations by introducing speech recognition technology, enabling users to interact with the calculator using their voice.

By leveraging the capabilities of the Python programming language and various libraries, the Voice-Activated Calculator transforms spoken words into actionable calculations. The program uses audio processing techniques and Mel-frequency cepstral coefficients (MFCC) to extract features from spoken words and identify the corresponding digits and operations. With this approach, users can effortlessly perform calculations without the need for manual input.

## Features

- Speech recognition: The calculator can recognize spoken digits (0-9) and operations ("plus" and "minus") from an audio file.
- MFCC extraction: Mel-frequency cepstral coefficients are extracted from the audio to capture relevant speech features.
- Dynamic Time Warping (DTW): The program uses DTW to find the most similar reference audio for accurate recognition.
- Graphical User Interface (GUI): The calculator provides a user-friendly GUI to facilitate easy interaction and display calculation results.
- Error handling: The program includes error handling to ensure accurate calculations and provide appropriate feedback.

## Prerequisites

To run the Voice-Activated Calculator, ensure that you have the following dependencies installed:


- Python (version 3.6 or higher)
- NumPy
- SciPy
- Librosa
- Python Speech Features
- FastDTW
- Tkinter

You can install the required dependencies using pip:

```
pip install numpy scipy librosa python_speech_features fastdtw tkinter
```

## Usage

1. Clone the repository and navigate to the project directory.

2. Prepare your audio files:

   - Place the audio files for digits (0-9) in a folder.
   - Place the audio files for operations ("plus" and "minus") in another folder.

3. Update the `digits_folder` and `operations_folder` variables in the code to point to the respective folders containing your audio files.

4. Run the program:

   ```
   python voice_calculator.py
   ```

5. The graphical user interface (GUI) will open.

6. Click on the "Select Audio File" button to choose an audio file (.wav) for calculation.

7. The program will process the audio file and display the result on the GUI.

## TEST 
<img width="572" alt="Screenshot 2023-07-15 at 12 55 04" src="https://github.com/Yassine-Squalli-Houssaini/Voice-Activated-Calculator-Streamlining-Calculations-with-Speech-Recognition/assets/127676452/2f488c7d-336c-4eff-8d5c-02a9072fb8aa">

<br>
<br>

### The Result

<img width="374" alt="Screenshot 2023-07-15 at 12 55 10" src="https://github.com/Yassine-Squalli-Houssaini/Voice-Activated-Calculator-Streamlining-Calculations-with-Speech-Recognition/assets/127676452/13f18246-7276-484c-bc29-4742ea8716b3">



## Conclusion

The Voice-Activated Calculator represents a significant advancement in simplifying mathematical calculations through speech recognition. By combining audio processing techniques, MFCC feature extraction, and DTW-based comparison, the program accurately recognizes spoken digits and operations, allowing for efficient and error-free calculations.

Whether you need to perform quick calculations or prefer a more interactive and intuitive approach, the Voice-Activated Calculator offers a streamlined solution. Experience the convenience of voice-activated mathematics and enjoy a new way of engaging with calculations.


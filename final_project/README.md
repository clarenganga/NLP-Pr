Language Identifier: 
This is a simple language detector/identifier program that takes a text input and predicts the language of the text.

Requirements: 
The following dependencies are required to run the program:
  Python 3.x
  langdetect library
  scikit-learn library
  numpy library
  gradio library
  
  lang_dataset.csv: (Link to file in Google Drive) https://drive.google.com/file/d/1YQ8dOVXudSL7YpP6uk7rF_Ju5Hj2ypy8/view?usp=share_link
  
Installation: 
To install the dependencies, you can use pip:
  pip install langdetect scikit-learn numpy gradio
  
Usage: 
To use the language detector/identifier program, run the following command in the terminal:
  python language_detector.py
This will start the program and open a web browser with the Gradio user interface. You can enter a text input and the program will predict the language of the text.
The program uses the langdetect library to detect the language of the text. If the language cannot be detected, the program uses a trained model to predict the language.

LICENSE: 
This program is licensed under the MIT License.

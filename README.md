Convert PDF to Audiobook

Reading stories or essays or any text can be arduous, 
however an audio reading of the text is convenient and doesnt require as much concentration as reading requires. 
In this project, I implemented a simple PDF to audio converter. 
This code scans page(s) of PDF and reads it using audio, to the user. 
While this project is good for simple text reading, it does not perform good if a scientific paper with equations is 
given to it because equations are not supported to be read in pytesseract OCR library which we used to convert image to text.


The software libraries required to run this code:

Pillow           # -------- image reader library.
PyMuPDF          # -------- library to convert PDF page to image.
pytesseract      # -------- Image to text converting Optical Character Recognition library.
pygame           # -------- pygame to play audio.
gTTS             # -------- Google Text To Speech.
pysimplegui      # -------- This library makes GUI development far simpler than tkinter.
tesseract        
tesseract-ocr
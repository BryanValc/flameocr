# flameocr
This is a program made using python, it uses Google's tesserocr, when you hit the PrtSc button it overrides it and displays you a red square, when u finish selecting the area, it takes a screenshot of it, runs the OCR, and loads the text to your clipboard



In order to get this to work you need to create a venv, in order to do so I recommend you watching this video: https://www.youtube.com/watch?v=ohlRbcasPAc

Once you created the venv, you must install the libraries by running this command in the console: "pip install -r requirements.txt"

After that, you must install tesseract-ocr: https://tesseract-ocr.github.io/tessdoc/Downloads.html
I recommend you to install it in the same folder where the main.py is located, create a folder named redist,
you should have something like this: https://i.imgur.com/F50K0zF.png	https://i.imgur.com/2TmXAUP.png

If you have it installed already, you can change pytesseract path at line 82 inside the main.py

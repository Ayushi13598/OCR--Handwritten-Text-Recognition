# OCR--Handwritten-Text-Recognition

##Idea
Train a light-weight network to solve word-level handwritten text recognition on images.

##Program Structure
Proces of recognition is divided into 4 steps. The initial input is a photo of page with text.

1.Detection of page and removal of background
2.Detection and separation of words
3.Normalization of words
4.Separation and recegnition of characters (recognition of words)

The folders available withing the repository:
1. Data- It is the folder where the input images are to be put.
2. Src- It contains all the required files that are needed for the main file to run and recognise handwritten text from input images.
3. Txt- Contains the output file that is the text recognised from the input image in the form of .txt

##Getting Started
Initially you need to clone the repository followed by installing the requirements file.
Then run the main.ipynb file after changing the image folder path(where you have the input images i.e. to be recognised for text) and text folder path(where you need the input txt file.)

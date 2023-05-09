# Text-Recognition-OCR
![image](https://user-images.githubusercontent.com/91408631/237001420-8a559e6a-d4b3-4491-a5de-fbaf8c515282.png)

##### •	OCR stands for optical character recognition.\n
##### •	Recognizing hand-written and printed characters that can be recognized and converted into machine readable text

## Objective:  To overview the exiting OCR techniques and find what suits best for our dataset. 
## Data:  Kaggle OCR Dataset
# Different Techniques used in OCR #
## •	Pre-Processing:
 ##### o	Improvement of image data
 ##### o	Supression of unwanted distortions and removal of noise
## •	Character Recognition:
 ##### o	Feature extraction is extracting out reduced set of features
 ##### o	Those features extracted are important ones and redundant ones are knocked out
## •	Post-Processing
 ##### o	Error Correction and Accuracy improving technique
 ##### o	Accuracy can be further improved by using lexicon, which implied algo has list of words to refer to as allowed words
 ##### o	OCR systems are accompanied by image scanning and optimization techniques
 
# OCR Tools: #
## >Tesseract: 
 ##### o	Open SOurce OCR
 ##### o	Converts Text and Graphic Elements into bitmap , which is black and white dots.
 ##### o Less accurate on handwritten texts and needs to be coupled and applied pre-processing techniayes for better accuracy on images
 
## >Keras OCR:
 ##### o	Provides out of the box ocr models
 ##### o	An end to end training pipeline to build new models and has intelligent character recognition for identifying languages.
 ##### o higher accuracy on pdf, image and handwriting recognition.


## >Easy OCR
 ##### o	o	EasyOCR is built with Pytorch library,and having a GPU speeds up the whole process of detection.
 ##### o	Has high accuracy and multi-language support
 ##### o Works better on structured data.
 
# Deliverables:  Comaprison between Easy OCR and Keras OCR

# Notebook Structure
## 1.Imports
## 2.Data Imports
## 3.Vizualization
## 4.Using Keras OCR
## 5.Using Easy OCR
## 6.Comparison Between Easy OCR and Keras OCR
## 7.Plotting results of comparison

# Results of comparison can be analyzed from the picture below
![image](https://user-images.githubusercontent.com/91408631/237022064-57bfa120-5e1c-47cd-aab1-4530a94351b7.png)
As it can be clearly seen Keras OCR works better on our dataset than Easy OCR. Both have nearly the same accuracy in real-life but the dataset differs for both the cases. Since ours was a image dataset Keras works better for us.
#### How to know if Keras OCR would be a better option or Easy OCR?
Keras-OCR is image specific OCR tool. If text is inside the image and their fonts and colors are unorganized. Easy-OCR is lightweight model which is giving a good performance for receipt or PDF conversion. It is giving more accurate results with organized texts like PDF files, receipts, bills.

# Overall Accuracy Comaprison:
##### Pytesseract: 60-70% on handwriting detetction and 80 to 95% on printed text 
##### Kerasocr:  90 to 95% detection on printed images, handwriting, pdf reading etc
##### Easyocr: upto 95% accuracy.write OCR texts in 70+ languages

# Conclusion:
##### o	Tesseract is performing great for high-resolution pictures. Certain morphological activities, for example, expansion, disintegration, and OTSU binarization can help increment pytesseract execution.
##### o	EasyOCR is a lightweight model which is giving a decent execution for receipt or PDF change. It is giving more precise outcomes with coordinated texts like pdf records, receipts, and bills.
##### o	Keras-OCR is a picture explicit OCR device. Assuming text is inside the picture and their textual styles and varieties are disorderly, Keras-ocr gives great outcomes.
##### o	Though there are no firm guidelines, we can consider the over three focuses while attempting to decide on an OCR instrument.

## Contact: sonakshichauhan1402@gmail.com

# Project Continuity
This is project is complete

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.





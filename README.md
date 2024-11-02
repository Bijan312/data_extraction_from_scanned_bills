# Data Extraction from Scanned Bills
Using python, I tried to extract electricity consumption data, which is in Persian, from scanned bills. In this way, one of tables in each page selected through defining an area of interest. Then, the data extracted. Having bills in Arabic alphabet limited the choices into image processing. And I find pytesseract a very beneficial library for such a goal.
<br/>
**pytesseract** is a Python wrapper for Google's **Tesseract-OCR engine**, which is an open-source tool for Optical Character Recognition (OCR). This library enables Python users to extract text from images, which is especially useful for processing scanned documents, photos of text, and images with embedded text.
<br/>
### Key Features
* **Image-to-Text Extraction:** pytesseract can convert text from image files (e.g., PNG, JPEG) into editable text formats, making it possible to automate data extraction from images.
* **Multilingual Support:** Tesseract supports multiple languages and even allows combining language packs to improve OCR accuracy for multilingual documents.
* **Integration with Pillow:** It can be used with the Pillow library (Python Imaging Library, or PIL) to preprocess images before OCR, which often improves recognition accuracy.
* **PDF Handling:** pytesseract can convert PDF files to images and then extract text, but it requires additional libraries like pdf2image.
<br/>
Consumptions are normalized based on the total energy used every day, and costs are normalized based on the total energy used in the period.
<br/>
The process of data mining and visualization depicted within the jupyter-notebooks.

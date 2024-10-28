# VisioNiX--Image_recognition_conversational_chatbot
An image recognition chatbot that can give brief explaination of the image according to the prompts

It appears the notebook is intended to generate captions for images using the BLIP (Bootstrapping Language-Image Pre-training) model and includes OCR (Optical Character Recognition) capabilities via Tesseract. Here's a draft README based on the initial inspection:

---

# VisioNiX

VisioNiX is an image captioning and optical character recognition (OCR) tool leveraging advanced language-image models and the Tesseract OCR engine. It generates descriptive captions for images and extracts embedded text using the BLIP model and Tesseract, respectively.

## Features

- **Image Captioning**: Generate detailed captions for images using BLIP (Bootstrapping Language-Image Pre-training).
- **OCR Extraction**: Extract embedded text from images using Tesseract.
- **Support for Language Processing**: Integrates with `language-tool-python` for grammar and language processing.
- **LLM Query Processing**: Utilises Cohere API to process queries and provide answers.
- **Python Package Integration**: Utilizes `transformers`, `torch`, and `pandas` for efficient processing and handling.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/VisioNiX.git
   cd VisioNiX
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Install Tesseract OCR:
   ```bash
   sudo apt-get install -y tesseract-ocr
   ```

## Usage

Run the notebook to perform image captioning and OCR on your images:

1. Load an image into the notebook.
2. Run the provided cells to generate captions and extract text.

## Requirements

- `transformers`
- `torch`
- `tesseract-ocr`
- `pytesseract`
- `pandas`
- `cohere` (optional for advanced NLP tasks)



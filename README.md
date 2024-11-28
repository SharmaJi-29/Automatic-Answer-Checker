# Automatic-Answer-Checker

## Overview

The Automatic Answer Checker is a software application designed to evaluate handwritten answers against a given set of correct answers. It utilizes OCR (Optical Character Recognition) and natural language processing (NLP) technologies to recognize text from handwritten submissions and assess them based on predefined criteria.

## Features

Handwriting Recognition: Extracts text from handwritten images using OCR.
Answer Evaluation: Compares recognized text with reference answers and grades responses.
Similarity Analysis: Uses NLP techniques to analyze semantic similarity between student answers and the correct ones.
Customizable Criteria: Allows for scoring based on keywords, sentence structure, and overall relevance.
Error Reporting: Highlights discrepancies between the handwritten response and the expected answer.

## Requirements

### Software
Python 3.8 or later
OCR Engine (e.g., Tesseract)
NLP Library (e.g., SpaCy, NLTK, or Hugging Face Transformers)

### Modules 
opencv-python
pytesseract
PIL
scikit-learn
nltk
os
tkinter


## Usage

### Prepare Input Files:
Save handwritten answer sheets as images (e.g., JPEG, PNG).
Store reference answers in a text or CSV file.

### Run the Checker:
python answer_checker.py --input <path_to_images> --answers <path_to_reference_answers>

### View Results:
Graded results will be saved in the output/ directory as a CSV or JSON file.
Detailed reports (optional) include detected handwriting and marked discrepancies.

## Acknowledgments

Tesseract OCR
SpaCy
NLTK
OpenAI for NLP inspiration.

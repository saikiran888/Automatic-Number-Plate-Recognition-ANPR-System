# Automatic-Number-Plate-Recognition-ANPR-System

## Overview

This project leverages the following technologies:
- **OpenCV:** For image processing, filtering, and contour detection.
- **EasyOCR:** For extracting text from images using Optical Character Recognition (OCR).

## Installation

To get started, clone this repository and install the required dependencies:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt

## Key Features

### Image Preprocessing with OpenCV:

- **Convert images to grayscale.**
- **Apply noise reduction using bilateral filtering.**
- **Perform edge detection using the Canny algorithm.**

### Contour Detection:

- **Detect contours to locate potential number plates.**
- **Mask and isolate number plate areas.**

### Text Extraction with EasyOCR:

- **Recognize and extract text from isolated number plates.**
- **Display and overlay extracted text on images.**

### Flexible Image Support:

- **Process multiple images with different formats.**
- **Easily customizable for various image resolutions.**

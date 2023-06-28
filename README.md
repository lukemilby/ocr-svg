# OCR API with FastAPI and Tesseract

This project is an OCR (Optical Character Recognition) API built using FastAPI and Tesseract. It allows you to extract text from images through a simple and easy-to-use REST API.

## Requirements

- Python 3.7+
- FastAPI
- Tesseract
- Uvicorn (ASGI server)
- Poetry

## Getting Started

Before running the application, make sure you have Python installed. You will also need to install Tesseract OCR engine. Here's how you can install it on various platforms:

### Install Poetry
```sh
curl -sSL https://install.python-poetry.org | python -
```
Install Dependencies
```sh
poetry install
```

### Ubuntu

```sh
sudo apt-get update
sudo apt-get install tesseract-ocr
```

### macOS
```sh
brew install tesseract
```

## Run application
```sh
poetry run uvicorn main:app --reload
```
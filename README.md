tesseract-vs2013
================

Tesseract OCR engine dependencies with VS 2013 support, both 64 and 32 bit.

This repository contains the dependencies for Google's [Tesseract OCR project](https://code.google.com/p/tesseract-ocr/) for tesseract 3.03 and leptonica 1.70, along with dependencies for everything but WEBP support.

### Build Instructions

1. Open VS 2013 Developer Command Prompt and change the directory to this repository.
2. Execute the following command ``msbuild build.proj``

The build libraries and headers will be copied to ``~\release`` when done.
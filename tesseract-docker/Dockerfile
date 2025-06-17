FROM ubuntu:22.04

# Installation von tesseract und deutschem Sprachpaket
RUN apt-get update && apt-get install -y \
    tesseract-ocr \
    tesseract-ocr-deu \
    libtesseract-dev \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

# Default command, damit Container am Leben bleibt
CMD ["tail", "-f", "/dev/null"]

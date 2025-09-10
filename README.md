PDF Converter Tool

A simple Python-based PDF Converter with a Tkinter GUI that allows users to perform common PDF operations with ease. The tool provides three main features:

Convert images (JPG/PNG) into PDF.

Split a PDF into individual pages.

Merge two PDF files into one.

Built using PyPDF2, img2pdf, and Pillow, this project is lightweight, user-friendly, and designed for quick PDF management tasks.

Features

Convert images to PDF with one click.

Split PDFs into single-page files.

Merge multiple PDFs into a single document.

Simple and interactive Tkinter GUI.

Installation

Clone this repository or download the source code.

git clone https://github.com/your-username/pdf-converter.git
cd pdf-converter


Install dependencies:

python -m pip install -r requirements.txt


Run the application:

python "PDF Converter.py"

Requirements

Python 3.x

Libraries:

PyPDF2

img2pdf

Pillow

(Already listed in requirements.txt)

Usage

Convert: Load an image (JPG/PNG) → Save as PDF.

Split: Load a PDF → Select folder → Split into individual PDFs.

Merge: Load two PDFs → Save as merged PDF.




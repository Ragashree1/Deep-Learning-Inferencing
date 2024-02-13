## Introduction

This repository contains code for extracting tables from PDF documents using the TableTransformerForObjectDetection from Hugging Face and the Tabula library. The process involves several steps, including converting the PDF to images, preprocessing the images, and utilizing the Hugging Face feature extractor for detection.

## Installation

To install the necessary dependencies, run the following commands:

```bash
!pip install -q git+https://github.com/huggingface/transformers.git
!pip install -q timm
!pip install --upgrade pymupdf
!pip install tabula-py ```

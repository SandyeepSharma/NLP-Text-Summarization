# Text Summarization with BART and PyMuPDF

This Python script leverages BART, a powerful sequence-to-sequence model for text summarization, along with PyMuPDF for handling PDFs. It extracts text from a PDF, generates a summary using BART, and saves the summary as a new PDF.

## Requirements

Make sure you have the necessary Python libraries installed:

```bash
pip3 install PyMuPDF transformers 
pip3 install torch torchvision torchaudio
```

## Usage
1. Clone the repository: 
```bash
git clone https://github.com/SandyeepSharma/Text-Summarization.git
cd Text-Summarization
```

2. Run the script with your PDF file:
```bash
python text_summarization.py
```

This example summarizes the content of the firesafety.pdf file.

## Customization
Feel free to customize the script based on your needs. Adjust parameters, modify the summarization approach, or integrate it into a larger project.

## Acknowledgments  
[PyMuPDF](https://pymupdf.readthedocs.io/en/latest/)  
[Transformers](https://huggingface.co/docs/transformers/index)  
Happy summarizing!
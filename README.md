# PDF3 Version 3 ||  PDF3 Version 4 ||  PDF3 Version 5
PDF->MP3
This Python application facilitates the conversion of PDF documents into MP3 audio files. It utilizes tkinter for a user-friendly interface, allowing selection of PDF files and output directories. The conversion process employs pyttsx3 and gTTS libraries to convert text extracted from PDFs into speech, offering options to choose voices including Sinhala language support.

## Installation & Setup

### Prerequisites
- Python 3.6 or higher
- pip (Python package manager)

### Steps to Run

1. **Clone or download the project**
   ```bash
   cd PDF-to-.MP3-Convertor
   ```

2. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python pdf3.py
   ```

### Dependencies
- `pdfminer.six` - For extracting text from PDF files
- `pyttsx3` - For converting text to speech

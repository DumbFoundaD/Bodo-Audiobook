# Bodo Audiobook Generator

This project allows users to upload files in various formats (TXT, PDF, DOCX) and converts them into audiobooks in the Bodo language.

## Features
- Accepts multiple file formats (TXT, PDF, DOCX).
- Translates text to Bodo (if not already in Bodo).
- Converts Bodo text to speech using Text-to-Speech (TTS).
- Generates audiobook files in MP3 format.

## Setup
### Prerequisites
- Python 3.8 or higher
- Install the dependencies: `pip install -r requirements.txt`

### Run the Application
```bash
python main.py
```

### Directory Structure
- `file_handler/`: Handles file input and text extraction.
- `translation/`: Manages text translation to Bodo.
- `tts/`: Converts text to speech in Bodo.
- `output/`: Stores the generated audiobook files.

## Future Improvements
- Add support for more input formats.
- Optimize translation and TTS for better performance.

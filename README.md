# Text Summarizer Dashboard

This is a web application for summarizing text and PDF documents using extractive and abstractive methods. It also supports translation of summaries to Hindi.

## Features

- Summarize text or PDF files (extractive or abstractive)
- View evaluation scores (ROUGE, BLEU, Precision, Recall)
- Translate summaries to Hindi
- Copy or download summaries
- Dark mode support

## Usage

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run the app:
   ```
   python app.py
   ```

3. Open your browser and go to `http://localhost:5000`

## File Structure

- `app.py` - Main Flask backend
- `templates/index.html` - Frontend HTML
- `static/style.css` - Stylesheet
- `static/script.js` - Frontend JS

## Requirements

See [requirements.txt](requirements.txt) for Python dependencies.

# TalkPDF

Streamlit app that lets you upload a PDF and ask it questions in plain English.

## Tech Stack
- Python
- Streamlit
- OpenAI API
- pdfplumber
- python-dotenv

## What it demonstrates
Document Q&A with an LLM — built to cut through dense research papers and clinical guidelines without reading cover to cover.

## How to run
```bash
git clone https://github.com/AhmedShehata2002/talkpdf
cd talkpdf
pip install -r requirements.txt
```

Create a `.env` file:
```
OPENAI_API_KEY=your_key_here
```

```bash
streamlit run app/main.py
```

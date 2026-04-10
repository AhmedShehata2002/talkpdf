# 📄 TalkPDF — Conversational PDF Assistant

A Streamlit web application that lets you have a conversation with any PDF document. Upload a paper, report, or textbook — then ask it questions in plain English.

---

## Objective

Bridge the gap between dense scientific and academic content and the people who need to understand it. Built with science communication in mind — making research accessible without sacrificing accuracy.

---

## Features

- PDF upload — drag and drop any PDF document
- Text extraction — full document parsing via pdfplumber
- Conversational Q&A — ask questions and get contextual answers
- Source grounding — responses reference specific sections of the document
- Multi-turn conversation — maintains context across follow-up questions
- Simple UI — clean Streamlit interface, no technical knowledge required

---

## Repository Structure

- /app — Streamlit application code
- README.md — Project overview and documentation

---

## How It Works

1. User uploads PDF
2. pdfplumber extracts full text
3. Text chunked and stored in context
4. User asks a question
5. GPT API retrieves relevant chunks and generates answer
6. Answer displayed with source reference

---

## Why I Built This

As someone with a Medical Sciences background who works with dense research papers regularly, I built TalkPDF to solve my own problem — getting to the insight in a paper without reading every word. It is also directly relevant to science communication, one of my core interests.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![pdfplumber](https://img.shields.io/badge/pdfplumber-gray?style=flat)

---

## Setup

```bash
git clone https://github.com/AhmedShehata2002/talkpdf
cd talkpdf
pip install -r requirements.txt
streamlit run app/app.py
```

Add your OpenAI API key to a .env file:
OPENAI_API_KEY=your_key_here

---

## Use Cases

- Quickly extract key findings from research papers
- Query clinical guidelines without reading cover to cover
- Study aid for dense academic textbooks
- Due diligence on financial reports or legal documents

---

## What I'd Do Next

- Add RAG with vector embeddings for longer documents
- Support multi-document upload and cross-document querying
- Add Arabic language support for Arabic-language PDFs
- Deploy as a public web app on Streamlit Cloud

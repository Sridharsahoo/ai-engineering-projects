# WebBrief AI - A AI Website Summarizer

An AI-powered application that takes a website URL, extracts
the relevant webpage content, and generates a concise summary
using an LLM.

## Architecture

User
  ↓
Gradio UI
  ↓
Website Scraper
  ↓
Extracted Content
  ↓
LLM API
  ↓
Generated Summary
  ↓
User

## Technologies

- Python
- BeautifulSoup
- OpenAI API
- Gradio

## How to Run

```bash
pip install -r requirements.txt
python app.py
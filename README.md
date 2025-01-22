# PDF-Markdown-VisionParse
A simple Streamlit UI wrapper for [vision-parse](https://github.com/iamarunbrahma/vision-parse) to convert PDFs to Markdown using AI vision models.

## UI
![PDF to Markdown Conversion Interface](https://github.com/lesteroliver911/pdf-markdown-visionparse/blob/main/pdf-markdown-vision-parse-one.png)


## What it does
- Provides a simple web interface to convert PDFs to Markdown
- Supports multiple AI vision models:
  - OpenAI (GPT-4V)
  - Google Gemini
  - Meta's Llama & LLaVA
- Shows real-time conversion progress
- Displays markdown output page by page

## Getting Started
1. Clone this repo

2. Install requirements
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app
   ```bash
   streamlit run app.py
   ```

4. Get your API key
   - OpenAI API key from: https://platform.openai.com/api-keys
   - Google Gemini API key from: https://aistudio.google.com/app/apikey
   - For Meta Llama & LLaVA: Use Ollama API endpoint (default: http://localhost:11434)

5. Upload a PDF and convert!




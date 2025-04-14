# GPT-3.5 Web Text Extractor & Prompt Pipeline (Haystack)

This project leverages [Haystack](https://github.com/deepset-ai/haystack) and Hugging Face Transformers to extract textual content from websites and process it through an NLP pipeline using pretrained LLMs like GPT-2.

## 📦 Features

- 🌐 Web scraping using BeautifulSoup
- 🤖 Prompt-based NLP pipeline using Haystack
- 🧠 Integration with Hugging Face models (GPT-2, PromptNode)
- 🧪 In-memory document storage & retrieval with BM25
- ✅ Interactive prompt handling (secure token input)

## 🛠️ Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

Or manually install the key libraries:

```bash
pip install farm-haystack[colab] farm-haystack[inference] transformers==4.39.3 beautifulsoup4 requests torch
```

## 🔑 Setup

The notebook will prompt for your Hugging Face API token. Make sure you have a valid token from [HuggingFace.co](https://huggingface.co/settings/tokens).

## 🚀 How to Use

1. Upload the notebook to Google Colab or Jupyter.
2. Provide URLs to scrape.
3. The pipeline will extract and process the text via a customizable prompt model.

## 🧠 Example Use Cases

- News summarization
- Web content analysis
- Prompt-based knowledge extraction

---

**Author:** *Your Name Here*  
**License:** MIT

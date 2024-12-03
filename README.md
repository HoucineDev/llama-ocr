# LLama3.2-OCR

This project employs the advanced capabilities of Llama 3.2 Vision, combined with the interactive framework of Streamlit, to develop a robust, locally hosted Optical Character Recognition (OCR) application. The solution operates entirely offline, ensuring data privacy and security, while delivering high-performance text extraction from images.

## Ollama Installation

### Overview
Ollama is a powerful platform that enables scalable machine learning inference across distributed GPU networks. This guide will walk you through the process of downloading, installing, and using Ollama on your system.


### Installation

**Setup Ollama**:
   ```bash
   # setup ollama on linux 
   curl -fsSL https://ollama.com/install.sh | sh
   ```

**Run LLama3.2-vision model**
```bash
   # pull llama 3.2 vision model
   ollama run llama3.2-vision 
   ```

**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install streamlit ollama
   ```
For more about ollama and available model [https://ollama.com/library/llama3.2-vision](ollam.com)

### Clone this this Repository

To get started, clone the repository from GitHub:

```bash
git clone https://github.com/HoucineDev/llama-ocr
```

### Run th app

```python
# run the app
streamlit run app.py
```

After running the command, Streamlit will launch a local server and provide a URL, typically something like http://localhost:8501/. You can open this in your browser to view the app.
# Ollama PDF Chat

A Python application that allows you to chat with your PDF documents using Ollama. This tool uses local LLMs to answer questions about the content of your PDF files.

## Prerequisites

- Python 3.8 or higher
- [Ollama](https://ollama.ai/) installed and running locally

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/ollama-pdf-chat.git
cd ollama-pdf-chat
```

2. Create a virtual environment and activate it:
```bash
python3 -m venv venv
source venv/bin/activate
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Make sure Ollama is running on your machine.

2. Run the application by providing a PDF file as an argument:

    ```bash
    python main.py path/to/your/document.pdf
    ```

3. Once the application starts, you can ask questions about the content of your PDF. The application will use the local LLM to provide answers based on the document's content.

4. To exit the application, press Ctrl+C.

## Example

```bash
$ python main.py kubernetes_tutorial.pdf
What do you want to learn from the document?
> What is this tutorial about?

[The application will process your question and provide an answer based on the PDF content]
```

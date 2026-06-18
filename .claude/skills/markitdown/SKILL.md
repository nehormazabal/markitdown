---
name: markitdown
description: Convert files (PDF, Word, Excel, PowerPoint, images, audio, HTML, CSV, JSON, XML, ZIP, YouTube URLs, etc.) to Markdown using the MarkItDown package from this repo. Use when the user asks to convert a document/file/URL to Markdown, extract text from a file as Markdown, or summarize a document's content.
---

# MarkItDown

Convert files and URLs to Markdown using the `markitdown` package contained in this repository (`packages/markitdown`).

## Setup

Ensure the package is installed in the current environment (only needed once):

```bash
pip install -e packages/markitdown[all]
```

## Usage

### Command line

```bash
markitdown path-to-file.pdf > document.md
```

Convert and print directly:

```bash
markitdown path-to-file.docx
```

It also accepts a URL (e.g. a YouTube link) wherever a file path is expected.

### Python API

```python
from markitdown import MarkItDown

md = MarkItDown()
result = md.convert("test.xlsx")
print(result.text_content)
```

For untrusted input, prefer the narrowest conversion method (e.g. `convert_stream()`) instead of `convert()`/`convert_local()`, since MarkItDown performs I/O with the privileges of the current process.

## Notes

- Supported formats include PDF, PowerPoint, Word, Excel, Images (EXIF/OCR), Audio (EXIF/transcription), HTML, CSV, JSON, XML, ZIP, and YouTube URLs.
- The optional `markitdown-mcp` package (`packages/markitdown-mcp`) exposes this same conversion as an MCP server.
- The optional `markitdown-ocr` plugin (`packages/markitdown-ocr`) adds OCR-based conversion for images/scanned documents.

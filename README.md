# PDF local LLM demo
> Convert PDF to text and process the text through an LLM

<!-- Badges generated with https://michaelcurrin.github.io/badge-generator/ -->
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/pdf-local-llm?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/pdf-local-llm/tags/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Python](https://img.shields.io/badge/dynamic/toml?url=https%3A%2F%2Fraw.githubusercontent.com%2FMichaelCurrin%2Fpdf-local-llm%2Frefs%2Fheads%2Fmain%2Fpyproject.toml&query=project.requires-python&label=python&logo=python&logoColor=white)](https://python.org "Go to Python homepage")
[![Poetry 2](https://img.shields.io/badge/poetry-2-blue)](https://python-poetry.org/ "Go to Poetry homepage")

## Use cases

- Translate a PDF to another language or rewrite in summarized format.
- Scale to a lot of content - if you have a lot of PDFs or many pages.
- Process data securely for privacy - run through the local LLM model offline, rather than using ChatGPT or a PDF translation service on the internet where you data might be used or stored.

## Limitations

- The translation example breaks the contents into chunks and processes them one chunk at a time. This works for translation but not for summarization or asking other questions.
- For the other approach, we pass the entire PDF contents to the LLM. Which can mean poor performance of quality.
- PDFs which exceed the token limits for the model will be cut off.

## Requirements

- [Python](https://www.python.org/)
- [Poetry](https://python-poetry.org/)
- [Ollama](https://ollama.com/)


## Installation

Install Python and Poetry as per versions at the top of this page.

Install project packages:

```sh
make install
```

Install Ollama using the _Download_ page of their website.


## Usage

1. Open VS Code.
1. Open [main.ipynb](/main.ipynb).
1. Select kernel as `.venv/bin/python`.
1. Run all cells.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).

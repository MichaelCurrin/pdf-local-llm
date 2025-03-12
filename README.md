# PDF local LLM demo
> Convert PDF to text and process the text through an LLM

<!-- Badges generated with https://michaelcurrin.github.io/badge-generator/ -->
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/pdf-local-llm?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/pdf-local-llm/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)


## Use cases

- Translate a PDF to another language or rewrite in summarized format.
- Scale to a lot of content - if you have a lot of PDFs or many pages.
- Process data securely for privacy - run through the local LLM model offline, rather than using ChatGPT or a PDF translation service on the internet where you data might be used or stored.


## Requirements

- [Python](https://www.python.org/).
- [Poetry](https://python-poetry.org/).
- [Ollama](https://ollama.com/).


## Installation

Install Ollama using the _Download_ page of the website.

Install project packages:

```sh
poetry install
```


## Usage

1. Open VS Code.
1. Open [main.ipynb](/main.ipynb).
1. Select kernel as `.venv/bin/python`.
1. Run all cells.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).

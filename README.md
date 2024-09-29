<a href="https://x.com/alxfazio" target="_blank">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="images/firecrawl-devdocs-to-llm-cover.png">
    <img alt="OpenAI Cookbook Logo" src="images/firecrawl-devdocs-to-llm-cover.png" width="400px" style="max-width: 100%; margin-bottom: 20px;">
  </picture>
</a>

Turn any developer documentation into a specialized GPT.

## Overview

DevDocs to LLM is a tool that allows you to crawl developer documentation, extract content, and process it into a format suitable for use with large language models (LLMs) like ChatGPT. This enables you to create specialized assistants tailored to specific documentation sets.

## Features

- Web crawling with customizable options
- Content extraction in Markdown format
- Rate limiting to respect server constraints
- Retry mechanism for failed scrapes
- Export options:
  - Rentry.co for quick sharing
  - Google Docs for larger documents

## Usage

1. Set up the Firecrawl environment
2. Crawl a website and generate a sitemap
3. Extract content from crawled pages
4. Export the processed content

## Requirements

- Firecrawl API key
- Google Docs API credentials (optional, for Google Docs export)

## Installation

This project is designed to run in a Jupyter notebook environment, particularly Google Colab. No local installation is required.

## Configuration

Before running the notebook, you'll need to set a few parameters:

- `sub_url`: The URL of the documentation you want to crawl
- `limit`: Maximum number of pages to crawl
- `scrape_option`: Choose to scrape all pages or a specific number
- `num_pages`: Number of pages to scrape if not scraping all
- `pages_per_minute`: Rate limiting parameter
- `wait_time_between_chunks`: Delay between scraping chunks
- `retry_attempts`: Number of retries for failed scrapes

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2024-present, Alex Fazio

---

[![Watch the video](https://i.imgur.com/VKRoApP.png)](https://x.com/alxfazio/status/1826731977283641615)

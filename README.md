# AI Web Scraper 

This project is a web scraper that extracts specific content from a given webpage based on user-defined descriptions. It uses **Selenium** for web scraping, **BeautifulSoup** for content parsing, and **Ollama LLM** for natural language processing to parse and extract information from the scraped content.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [How It Works](#how-it-works)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

This AI Web Scraper project allows you to scrape content from any public webpage and parse specific information based on user queries. The scraper uses Selenium to load the page, BeautifulSoup to extract the body content, and Ollama LLM to intelligently parse the content based on your description.

## Features

- Scrapes any webpage using Selenium.
- Extracts and cleans the body content using BeautifulSoup.
- Uses Ollama LLM for intelligent parsing of content based on user descriptions.
- Allows users to input a URL, scrape the website, and provide a description for targeted content extraction.
- View the DOM content and parsed results in an interactive web interface built with Streamlit.

## Requirements

To run this project locally, you’ll need to install the following dependencies:

- Python 3.x
- `selenium`
- `beautifulsoup4`
- `streamlit`
- `webdriver_manager`
- `langchain_ollama`
- `langchain_core`

You can install the required dependencies using `pip`:

```bash
pip install selenium beautifulsoup4 streamlit webdriver_manager langchain_ollama langchain_core

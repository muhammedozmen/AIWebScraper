# AI Web Scraper

This repository contains a Streamlit application that scrapes websites to extract content and utilizes AI to analyze specific content within those websites. The application provides a user-friendly interface for managing website scraping, viewing extracted content, and performing AI-driven analysis on specific elements.

## Features

- **Website Scraping**: Automatically scrape websites to extract and store content for further analysis.
- **Content Analysis**: Use AI to analyze specific content within the scraped websites, focusing on keywords, sentiment, or other criteria.

## Installation

### Prerequisites

- Python 3.7 or higher
- Cloudinary account

### Setup

1. Clone the repository:

   ```
   git clone https://github.com/muhammedozmen/AIWebScraper.git
   cd AIWebScraper
   ```

2. Create and activate a virtual environment:

   ```
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```
   pip install -r requirements.txt
   ```

4. Download Ollama:

   ```
   https://ollama.com/download
   ```

5. Run Ollama and llama3:

   Open the command prompt and run:
   ```
   ollama run llama3
   ```

6. Run the application:

   ```
   streamlit run main.py
   ```

## Usage

### Scraping Websites

You can scrape websites using the `scrape.py` script. The content from the websites will be extracted and stored for further analysis.

### Content Analysis

Use the `parse.py` script to apply AI algorithms on the scraped content. The analysis can focus on specific content within the websites, such as keyword extraction, sentiment analysis, or other user-defined criteria.

## Code Overview

- `main.py`: The main Streamlit application that provides a user interface for scraping websites, analyzing content, and viewing results.
- `parse.py`: Contains functions for processing scraped content using AI, focusing on specific content analysis.
- `scrape.py`: Includes the script for scraping websites and extracting content.

## Dependencies

- `streamlit`: For creating the interactive web application interface.
- `langchain`: For building and managing complex AI workflows powered by large language models.
- `langchain_ollama`: For integrating LangChain with Ollama, enabling advanced AI-driven content analysis.
- `selenium`: For automating web browsing tasks, such as scraping dynamic websites that require interaction.
- `beautifulsoup4`: For parsing HTML and extracting data from static web pages.
- `python-dotenv`: For managing environment variables securely within the application.
- `lxml`: For fast and flexible XML and HTML processing, enhancing web scraping capabilities.
- `html5lib`: For parsing HTML documents in a way that closely mimics how web browsers parse them, ensuring compatibility with different web pages.

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

If you have any questions or suggestions, feel free to reach out via GitHub issues or LinkedIn.

# AI Web Scraper 🤖🌐

AI Web Scraper is a powerful and intuitive web scraping application that leverages Large Language Models (LLMs) to extract specific information from websites based on natural language commands. Instead of writing complex selectors, you can simply tell 🗣️ the AI what you want, and it will parse the data for you ✨.  
The application is built with a user-friendly interface using Streamlit, making it easy for anyone to scrape, view, and parse web content. 📊💻

# Key Features 🚀
* **Simple URL-based Scraping:** Enter any website URL to fetch its full DOM content. 🔗
* **Intelligent AI Parsing:** Uses Ollama with Llama 3.1 via LangChain to understand your requests and extract the exact information you need. 🧠🔍
* **Natural Language Queries:** No need for CSS selectors or XPath. Just ask for the data you want (e.g., "List all the article titles" or "Extract the product names and prices"). 💬💡
* **Interactive UI:** A clean and simple web interface built with Streamlit allows you to see the scraped content and interact with the AI parser easily. 🖥️✨
* **Content Cleaning:** Automatically removes unnecessary scripts and styles from the scraped HTML to provide clean text to the AI for better accuracy. 🧹📄

# Technologies Used 🛠️
### This project is built with a modern stack of Python 🐍 libraries for web scraping, AI integration, and web development.
* **Backend & Core:**
  * Python
* **AI & LLM Integration:**
  * LangChain: Framework for developing applications powered by language models 📖.
  * Ollama (`langchain_ollama`): For running the Llama 3.1 model locally. 🧠
* **Web Scraping:**
  * Selenium: For browser automation and scraping dynamic JavaScript-heavy websites 🕸️.
  * BeautifulSoup4: For parsing HTML and extracting/cleaning content 🍲.
* **Web Framework:**
  * Streamlit: For creating and running the interactive web application UI 📊.
* **Dependencies:**
  * lxml, html5lib: Efficient parsers for BeautifulSoup.
  * `python-dotenv`: For managing environment variables 🔑.

# Setup and Installation ⚙️
To run this project locally, you will need to have Python 🐍 and Ollama 🦙 installed.

## **1. Prerequisites: Install Dependencies 📥**

Download the given `req.txt` file on you machine and run:  
```sh
pip install -r req.txt
```
***Note: The `scrape.py` file is currently configured to use a remote Selenium WebDriver service (Bright Data). To run this locally without that service, you will need to modify scrape.py to use a local chromedriver 🔧.***

It'll install all the required libraries on your machine.  
You might as well crate a virtual environment on your machine before installing the dependencies by:

```python
python -m venv {your_venv_name}
``` 
## **2. Clone the Repository 📂**
Clone this repository to your local machine:

```bash
git clone https://github.com/Anindya4/AI-Web-Scrapper.git
cd AI-Web-Scrapper
```


















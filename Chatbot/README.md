
# Smartphone FAQ Chatbot

This project implements a chatbot to answer frequently asked questions (FAQs) about popular smartphones in Pakistan. The chatbot uses a combination of web scraping, natural language processing, and Gradio to provide accurate responses to user queries.

## Features
- **Web Scraping**: Scrapes smartphone data from the WhatMobile website.
- **FAQ Handling**: Processes JSON-based FAQs for better user interactions.
- **Interactive Interface**: Gradio-based UI for real-time Q&A.
- **NLP Techniques**: Uses spaCy and related libraries for natural language processing.

## Installation

### Prerequisites
- Python 3.10 or later
- An active internet connection for web scraping and dependencies

### Steps
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/smartphone-faq-chatbot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd smartphone-faq-chatbot
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Ensure all dependencies are installed.
2. Run the main script:
    ```bash
    python main.py
    ```
3. Access the chatbot interface in your browser using the provided Gradio link.

## Files
- `main.ipynb`: Contains the implementation of the chatbot and web scraping logic.
- `requirements.txt`: Lists the dependencies needed for the project.
- `README.md`: Documentation for the project.
- `faqs.json`: Sample FAQs for the chatbot.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
- **spaCy**: For natural language processing.
- **Gradio**: For building the interactive user interface.
- **WhatMobile**: For providing smartphone data.


# News Summarization with LLMs

This project demonstrates how to fetch the latest news articles and summarize them using Large Language Models (LLMs). It shows how to use LLMs to extract key points and generate concise summaries of news articles.

## Project Overview

The main notebook, `NewsSummarizer.ipynb`, walks through fetching news articles from reliable sources using APIs and then summarizing them with a language model. The system automatically extracts important information and condenses it into summaries.

Key components of this project:
- **LangChain Agents**: Used to manage interactions between different parts of the system.
- **OpenAI Functions**: Handles automatic function calls when needed.
- **ChatGPT**: Generates high-quality summaries from news articles.
- **Prompt Engineering**: Optimizes the input prompts to improve summarization.
- **NewsData API**: Fetches the latest news articles.
- **Python**: The whole system is implemented in Python.

By using these tools, we’ve created an efficient way to summarize news articles.

## Prerequisites

Before you start, make sure you have the following:
- Python 3.10 or higher
- Jupyter Notebook
- The required Python packages (listed in `requirements.txt`)
- Two environment variables:
  - `GROQ_API_KEY`
  - `NEWSDATA_KEY`

You can set these keys by exporting them in your terminal:
```bash
export GROQ_API_KEY="your_groq_api_key"
export NEWSDATA_KEY="your_newsdata_api_key"
```

Alternatively, you can add them to your `.env` file.

## Getting Started

1. Clone this repository to your local machine.
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the `NewsScraper.ipynb` notebook in Jupyter Notebook.
4. Follow the steps in the notebook to fetch news and generate summaries.

## Limitations

Currently, the word limit functionality for the summaries doesn’t work perfectly. While the summarization process itself works well, the word limit isn’t always enforced correctly.

Feel free to contribute and help improve the word limit feature!

## Contributing

If you have ideas or fixes, feel free to open a pull request. Just make sure to follow the project's coding style.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use or modify it as you need.

## Acknowledgments

Thanks to the developers of the libraries and tools used in this project for making this work possible.
```

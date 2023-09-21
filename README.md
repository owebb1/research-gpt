# Research Agent

A versatile research agent powered by OpenAI's `gpt-3.5-turbo` model and the `langchain` library. This application is designed to deeply research topics, extract and summarize content from web pages, and present information backed by references. It can be deployed and interacted with via Streamlit.

## Features

- **Advanced Research Capabilities**: Uses OpenAI's powerful language model for in-depth research.
- **Web Scraping Tool**: Extracts and summarizes content from given URLs.
- **Responsive Interface**: Streamlit-based UI for easy interaction.

## Prerequisites

- Python 3.8+
- `browserless` and `serper` API keys stored as environment variables.

## Installation

1. Clone the repository:

```
git clone <repository_url>
cd <repository_directory>
```

2. Install the required packages:

```
pip install -r requirements.txt
```

3. Set up the environment variables:

- Create a `.env` file in the root directory.
- Add your `BROWSERLESS_API_KEY`, `SERP_API_KEY`, and `OPENAI_API_KEY` to the `.env` file:

```
BROWSERLESS_API_KEY=your_browserless_key
SERP_API_KEY=your_serper_key
```

4. Start the Streamlit app:

```
streamlit run app.py
```

## Usage

1. Open the Streamlit app in your browser.
2. Input your research question into the text box.
3. Click on the 'Research' button to get the research results.

## Code Structure

- `app.py`: Main application code, which includes the definition of tools, the agent, and the Streamlit UI.
- `requirements.txt`: Contains the necessary Python packages to run the app.

## Contributing

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

## Feedback

If you have any feedback or issues, please open an issue in this repository.

## License

This project is open source and available under the [MIT License](LICENSE).

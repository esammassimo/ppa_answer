# People Also Ask (PAA) Generator

This Streamlit app fetches "People Also Ask" (PAA) questions from Google using Serper.dev and generates detailed answers using OpenAI's GPT-4.

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/streamlit-paa-generator.git
   cd streamlit-paa-generator
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
2. Enter your **Serper.dev API Key** and **OpenAI API Key**.
3. Provide a keyword to fetch related "People Also Ask" (PAA) questions.
4. Click **Generate PAA Questions and Answers**.
5. The app will display the questions and generate answers using GPT-4.
6. Use the **Copy to Clipboard** button to easily transfer the text to Word or other applications.

## Requirements

- Python 3.8+
- Streamlit
- Requests
- OpenAI Python SDK

## Notes

- The Serper.dev API Key is required to fetch questions from Google.
- The OpenAI API Key is required for generating answers.
- The app does **not** save data permanently.

## License

MIT License
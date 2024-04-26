# PDF Question Answering App

This is a Flask application that allows users to upload PDF files and ask questions about their content. The app uses natural language processing and machine learning models to understand the PDF content and provide relevant answers to the user's questions.

## Features

- Upload and process multiple PDF files
- Ask questions about the PDF content
- Get accurate and contextual answers

## Prerequisites

- Python 3.6 or higher
- Flask
- Langchain
- PyPDF2
- Google Generative AI API credentials

## Installation

1. Clone the repository:
2. Install the required packages:
pip install -r requirements.txt
3. Set up the Google Generative AI API credentials by creating a `.env` file with the following content:
GOOGLE_API_KEY=your_api_key_here

## Usage

1. Run the Flask app:
python app.py
2. Open your web browser and navigate to `http://localhost:5000`.
3. Click the "Process PDFs" button to select and upload your PDF files.
4. Enter your question in the text area and click "Ask" to get the answer.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


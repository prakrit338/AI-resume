# Resume PDF Question Answering App

This is a Flask application that allows users to upload resume PDFs and ask questions about the information contained within them. The app utilizes natural language processing and machine learning models to understand the resume content and provide accurate and relevant answers to the user's questions.

<img width="1390" alt="Screenshot 2024-02-16 at 4 37 36 PM" src="https://github.com/prakrit338/Gemini-Pro-LLM-Application/assets/72137633/10916c33-e9b0-47f2-af4a-bdee8d9daac7">


## Features

- Upload and process multiple resume PDFs
- Ask questions about the candidate's experience, skills, education, and more
- Get contextual and concise answers based on the resume content

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


# Resume PDF Question Answering App

This is a Flask application that allows users to upload resume PDFs and ask questions about the information contained within them. The app utilizes natural language processing and machine learning models to understand the resume content and provide accurate and relevant answers to the user's questions.


![Screenshot 2024-04-26 at 12 27 54 PM](https://github.com/prakrit338/AI-resume/assets/72137633/890da091-b415-4f96-8a8b-06d220099d04)

![Screenshot 2024-04-26 at 12 28 12 PM](https://github.com/prakrit338/AI-resume/assets/72137633/9c61a4a1-c40d-4347-8a26-76595703407f)
<img width="697" alt="Screenshot 2024-04-26 at 12 38 24 PM" src="https://github.com/prakrit338/AI-resume/assets/72137633/613e2c62-8547-4c89-93ea-c3a4a6807376">


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

1. ```bash
    git clone https://github.com/prakrit338/AI-resume.git
    ```
2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Set up the Google Generative AI API credentials by creating a `.env` file with the following content:

```bash
GOOGLE_API_KEY=your_api_key_here
```
## Usage

1. Run the Flask app:
```bash

python app.py
```

2. Open your web browser and navigate to `http://localhost:5000`.
3. Click the "Process PDFs" button to select and upload your PDF files.
4. Enter your question in the text area and click "Ask" to get the answer.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
Regarding any collab, mail to : 'prakrittimilsina338@gmail.com'


## License

This project is licensed under the [MIT License](LICENSE).



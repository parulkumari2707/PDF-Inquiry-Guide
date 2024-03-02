PDF-Inquiry-Guide
===
PDF Inquiry Guide is a Streamlit app that allows you to upload a PDF document and interactively ask questions about its content. The app extracts text from the uploaded PDF and provides answers to your questions based on the content of the document.

Description
==
PDF Inquiry Guide is designed to assist users in quickly extracting information from PDF documents through a simple and intuitive interface. Whether you're studying, researching, or simply exploring new topics, ChatPDF helps streamline the process of accessing relevant information within PDF files.

## Getting Started

To run the app locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required Python packages by running:
   ``` bash pip install -r requirements.txt```
5. Run the Streamlit app by executing:
   ``` bash streamlit run PDF_inquiry_app.py```
7. Access the app in your web browser at `http://localhost:8501 `.

Usage
===
1. Upload a PDF document using the file uploader.
2. Ask questions about the content of the PDF using the text input field.
3. Click the "Ask" button to submit your question.
4. The app will display the answer to your question based on the content of the PDF.

Dependencies
===
- Streamlit
- PyPDF4
- NLTK

File Structure
===
- `PDF_inquiry_app.py`: Main Python script containing the Streamlit app code.
- `requirements.txt`: File containing the list of Python dependencies.

Contributing
==
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your proposed changes.

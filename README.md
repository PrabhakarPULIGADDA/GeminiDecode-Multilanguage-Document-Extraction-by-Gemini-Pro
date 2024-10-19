  ***GeminiDecode***
     is an advanced application designed to extract and process data from documents in multiple languages. Leveraging cutting-edge natural language processing (NLP) and machine learning algorithms, this tool streamlines the analysis of diverse documents, making it ideal for businesses and professionals operating in multilingual environments.

## Key Features

- **Multilingual Support**: Seamlessly processes documents in over 50 languages, enhancing accessibility.
- **Custom Prompts**: Allows users to input specific queries, guiding the analysis to meet unique needs.
- **Image Upload Capability**: Supports document uploads in common image formats (JPG, JPEG, PNG).
- **Real-time Document Analysis**: Provides immediate feedback and insights based on the uploaded documents.
- **User-Friendly Interface**: Built with Streamlit for a smooth and intuitive user experience.

## Technologies Used

- **Streamlit**: A powerful framework for building interactive web applications with Python.
- **Google Generative AI**: Utilized for natural language processing and document analysis.
- **Python Libraries**:
  - `Pillow`: For image handling and processing.
  - `PyPDF2`: For PDF text extraction and manipulation.
  - `python-dotenv`: To manage environment variables securely.

## Installation Guide

#Follow these steps to set up the project locally:

 ## **Clone the Repository**:
   GeminiDecode-Multilanguage-Document-Extraction-by-Gemini-Pro.git
   
   cd GeminiDecode

 ## **Install Required Libraries**:
pip install -r requirements.txt

## **Create a .env File**:
in the root directory with your Google API key:
GOOGLE_API_KEY=your_google_api_key_here

## **Running the Application**:
To launch the application, execute the following command in your terminal:
streamlit run app.py


## Usage Instructions:
**Upload a Document**: Use the file uploader to select an image of your document.

**Enter a Custom Prompt**: Provide specific questions or instructions related to the document content.

**Analyze the Document**: Click the "Tell me about the document" button to receive insights based on your input.
## Acknowledgments:
**Streamlit**: For providing the framework that powers this application.

**Google Generative AI:** For its robust language processing capabilities.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Resume Feedback Agent

A web application that analyzes resumes and provides feedback on their content. The application supports PDF and DOCX file formats and provides insights about the resume's content, including word count, skills, and experience.

## Features

- Drag and drop interface for resume upload
- Support for PDF and DOCX files
- Real-time resume analysis
- Identifies skills and experience
- Modern, responsive UI
- Secure file handling

## Setup

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Download the spaCy model:
```bash
python -m spacy download en_core_web_sm
```

4. Run the application:
```bash
python app.py
```

5. Open your browser and navigate to `http://localhost:5000`

## Usage

1. Click the "Browse Files" button or drag and drop your resume file onto the upload area
2. Wait for the analysis to complete
3. View the feedback and insights about your resume

## Supported File Types

- PDF (.pdf)
- Microsoft Word (.docx)

## Security

- Files are processed securely and deleted immediately after analysis
- Maximum file size is limited to 16MB
- Only specific file types are allowed

## Technologies Used

- Flask (Backend)
- TailwindCSS (Frontend)
- spaCy (NLP)
- PyPDF2 (PDF processing)
- python-docx (DOCX processing) 
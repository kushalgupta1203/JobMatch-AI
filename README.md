# JobMatch AI 

**JobMatch AI** is a web application that evaluates the quality of resumes using an NLP model. Deployed with Flask, it allows users to upload their resumes and receive feedback on their effectiveness.

## Requirements

Create a virtual environment and install the required libraries using `requirements.txt`:

1. **Create a virtual environment:**

   ```bash
   python -m venv venv
   ```

2. **Activate the virtual environment:**

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Create and activate the virtual environment as described above.**

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask application:**

   ```bash
   python app.py
   ```

5. **Access the application:**

   Open your web browser and navigate to `http://127.0.0.1:5000`.

![Description of Image](https://github.com/kushalgupta1203/JobMatch-AI/blob/main/pictures/1.png)

![Description of Image](https://github.com/kushalgupta1203/JobMatch-AI/blob/main/pictures/2.png)

![Description of Image](https://github.com/kushalgupta1203/JobMatch-AI/blob/main/pictures/3.png)

![Description of Image](https://github.com/kushalgupta1203/JobMatch-AI/blob/main/pictures/4.png)

## Dependencies

- **Flask==2.3.2**: A lightweight WSGI web application framework.
- **docx2txt==0.8**: A library to extract text from DOCX files.
- **PyPDF2==3.0.1**: A library to extract text from PDF files.
- **scikit-learn==1.3.2**: A library for machine learning, used for feature extraction and similarity calculations.

## Usage

1. **Upload your resume:** Choose a DOCX or PDF file using the upload button on the web interface.
2. **Receive feedback:** After uploading, the system evaluates your resume and provides a quality score along with feedback.

## Features

- **Resume Upload:** Users can upload their resumes in DOCX or PDF format.
- **Resume Analysis:** The system analyzes the uploaded resume to provide a quality score based on various criteria.
- **Feedback Report:** Users receive feedback on their resume's content and formatting.

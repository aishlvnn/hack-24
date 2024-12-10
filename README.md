# hack-24
# QuizElevate  
**Where learning gets interactive!**

## Overview  
QuizElevate is a Flask-based web application designed to generate multiple-choice questions (MCQs) from user-provided text or PDF files. By leveraging Natural Language Processing (NLP), the application extracts meaningful information to create engaging and educational quizzes. 

## Features  
- **File Upload:** Supports PDF and text file uploads.  
- **Dynamic Question Generation:** Allows users to specify the number of MCQs (5, 10, 15, or 20).  
- **Interactive Interface:** Responsive design using Bootstrap for seamless navigation.  
- **NLP-Powered Insights:** Utilizes spaCy for sentence parsing and keyword extraction.  
- **Distractor Options:** Automatically generates plausible distractors for MCQs.  

## Technologies Used  
- **Backend:** Python, Flask, spaCy  
- **Frontend:** HTML, CSS (via Bootstrap), JavaScript  
- **File Handling:** PyPDF2 for PDF text extraction  
- **Styling:** Google Fonts

## How It Works  

1. **Input:** Upload a text or PDF file or manually enter text.  
2. **Processing:** The backend processes the content using spaCy for tokenization and named entity recognition.  
3. **MCQ Generation:** Questions are dynamically created with multiple answer choices, including distractors.  
4. **Output:** A list of MCQs is displayed for review or use.  

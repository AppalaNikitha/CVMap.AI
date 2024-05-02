**CVMap AI**

1. **CV Predict AI**:
   - This feature allows users to upload their existing resumes in PDF format.
   - The system then processes the content of the resume using natural language processing (NLP) techniques to extract key information such as skills, experiences, education, and achievements.
   - Once the information is extracted, CV Predict AI generates a set of subjective test questions relevant to the content of the resume. These questions are designed to help users prepare for interviews by prompting them to explain various aspects of their professional background.
   - The subjective test questions are generated dynamically based on the resume content, ensuring relevance and specificity to each user's profile.

2. **CV GenAI**:
   - This feature allows users to create resumes from scratch using an intuitive web interface.
   - Users input their personal details, educational background, skills, projects, internship experiences, achievements, and additional courses.
   - The system then generates a formatted resume document based on the provided information.
   - The generated resume includes sections for personal information, education, projects, skills, internships, achievements, and courses, presented in a         professional and structured manner.
   - The resume document is generated in PDF format, ready for download and submission to potential employers.

**Technologies Used**:
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python with Flask framework
- **Other Libraries**: PyPDF2, pdfminer, nltk

**Key Components**:
- **Data Processing**: Extraction of information from resumes using PyPDF2 and pdfminer libraries in Python.
- **Natural Language Processing (NLP)**: Utilization of nltk library for text processing, including tokenization and part-of-speech tagging.
- **Dynamic Question Generation**: Generation of interview questions based on resume content, tailored to each user's profile.
- **Resume Generation**: Creation of formatted resumes based on user input, ensuring professional presentation and structured content.

### For more details, please visit the following web link :
http://127.0.0.1:5000/

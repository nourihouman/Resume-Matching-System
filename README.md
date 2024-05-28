# Resume-Matching-System

## Project Workflow
Step 1: Import Necessary Libraries
The project utilises Python libraries such as spaCy for NLP tasks, pandas for data manipulation, and matplotlib for data visualization. Ensure all dependencies are installed using the provided requirements.txt.

Step 2: Load the Dataset
The dataset consists of 2400 resumes with the following columns:

ID: Unique identifier for each resume.
resume_str: Resume content in plain text.
resume_html: Resume content in HTML format.
Category: Job category associated with each resume.
For demonstration purposes, we randomly select 200 resumes to simplify processing and visualization.

Step 3: Clean Resume Data
A custom cleaning function is implemented to remove unwanted characters, stop words, and other extraneous elements from the resume_str column to prepare the data for NLP processing.

Step 4: Skill Extraction
Using spaCy and a custom JSON file containing 2500 predefined skills, the system identifies and extracts skills from each resume.

Step 5: Keyword Extraction
The system identifies key skills for each category (e.g., Information Technology) and uses these to enhance the matching process.

Step 6: Match Score Calculation
Users can enter required skills for a job, and the system calculates a match score for each resume, indicating the percentage of required skills present in the resume.

Contributing
Contributions to this project are welcome! Please fork the repository and submit pull requests with your suggested changes.

Credits
This project was inspired by challenges faced by recruiters in the tech industry and uses data provided by https://deepnote.com/app/abid/spaCy-Resume-Analysis-81ba1e4b-7fa8-45fe-ac7a-0b7bf3da7826?Job_Category=AVIATION

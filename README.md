# Resume-Screening-and-Job-Recommendation

## Introduction
The Resume Screening AI-Based System is a web application that leverages machine learning to assist recruiters in automating the process of categorizing resumes, recommending suitable job roles, and extracting essential information from resumes. This project enables users to upload resumes in either PDF or TXT format and receive recommendations and parsed resume details.

## Problem Statement
In traditional hiring processes, recruiters often face challenges when manually screening large volumes of resumes. This manual process is time-consuming, prone to human error, and can result in the omission of qualified candidates due to cognitive biases or fatigue. Additionally, categorizing resumes and matching candidates to suitable job roles requires expertise and attention to detail, which can be difficult to maintain under heavy workloads.

## Solution
The Resume Screening AI-Based System addresses these challenges by using machine learning models to categorize resumes and recommend job roles based on candidate qualifications. It also provides a resume parsing feature that extracts essential information such as contact details, skills, and education, allowing for a streamlined and efficient recruitment process.


## Project Overview
This project consists of a web interface and backend code, allowing users to:

⮞ Upload a resume in PDF or TXT format.

⮞ Categorize the resume based on predefined categories.

⮞ Receive job role recommendations based on resume content.

⮞ Parse the resume to extract key details, including the candidate's name, contact information, skills, and education.


## Dataset Used
Link: https://www.kaggle.com/datasets/noorsaeed/resume-datasets

## Technologies Used
➣ Jupyter Notebooks: Data preprocessing, feature engineering, model training and evaluation.

➣ Flask: Backend server to handle model requests and responses.

➣ HTML & CSS: Front-end interface for resume upload and recommendation display.

➣ Libraries: Pandas, NLTK, Scikit-learn (for TF-IDF, Cosine Similarity), Flask.


## Project Structure

The project files are structured as follows:

➣ Resume-Categorization.ipynb: A Jupyter notebook for training or testing the resume categorization model. This notebook includes data preprocessing steps and model training code.

➣ Resume-Job-Recommendation.ipynb: A Jupyter notebook focused on building and evaluating the job recommendation system based on extracted information.

➣ app.py: A Flask application that serves as the backend for handling file uploads, processing resumes, and returning categorized results and recommendations.

➣ resume.html: The HTML front-end file that provides the user interface for uploading resumes and displaying analysis results, including recommendations and extracted resume information.


## Methodology
### 1. Data Collection and Preprocessing
**➣ Data Source:** Collected datasets consisting of resumes and job descriptions.

**➣ Preprocessing Steps:**

-> Text Cleaning: Removed unnecessary characters, stop words, and punctuation.

-> Tokenization: Split text into individual words for easier processing.

-> Stemming/Lemmatization: Reduced words to their root forms for consistent analysis.

-> Vectorization: Applied TF-IDF (Term Frequency-Inverse Document Frequency) to convert text data into numerical form, capturing word importance and document similarity.



### 2. Feature Engineering
➣ Transformed text data into a structured format using TF-IDF Vectorizer.

➣ **Cosine Similarity Calculation:** Used cosine similarity to measure the similarity between resumes and job descriptions, enabling effective job recommendations.



### 3. Model Training and Evaluation
➣ Developed and trained a recommendation model to match resumes with relevant job descriptions.

➣ **Evaluation Metrics:** Used Precision, Recall, and F1 Score to assess model accuracy and fine-tune the model for better performance.



### 4. Backend Development (Flask Application)
➣ **Created a Flask backend to serve the model and handle requests.
**
➣ **Route Setup: Configured routes to:**

**-> **Accept resumes as input from the front end.

**-> **Process the data and apply the trained model.

**-> **Return job recommendations based on the similarity scores.



### 5. Frontend Development (HTML & CSS)

**➣ Developed a resume.html interface for recruiters to interact with the system.

➣ UI Features:**

 **->** Resume Upload: Allows users to upload resumes.

** -> **Job Recommendations Display: Shows the most relevant job roles based on the uploaded resume.

** -> **Integrated front end with the Flask backend for a seamless user experience.



### 6. System Workflow

**Step 1:** User uploads a resume through the HTML interface.

**Step 2:** The resume is sent to the Flask server, where it’s preprocessed.

**Step 3:** The model analyzes the resume and calculates similarity scores with job descriptions.

**Step 4:** The Flask server sends the recommended job roles back to the front end for display.



## Key Features
1: Resume Parsing: Our system utilizes NLP techniques to extract essential information from resumes, including contact details, skills, education, and work experience. This automated parsing eliminates the need for manual data entry and ensures accuracy and efficiency.

2: Categorization: Machine learning algorithms categorize resumes into predefined categories based on specific criteria set by recruiters or hiring managers. This categorization enables recruiters to quickly identify top candidates for further evaluation.

3: Job Recommendations: Leveraging machine learning models, our system recommends relevant job openings to candidates based on their skills, experience, and preferences. This personalized approach enhances candidate engagement and increases the likelihood of successful matches.


## Images

![WhatsApp Image 2024-11-04 at 23 36 42_ef657e27](https://github.com/user-attachments/assets/d5b15365-69a5-4ec2-8e29-ff73290ff9b8)

![WhatsApp Image 2024-11-04 at 23 37 15_76901575](https://github.com/user-attachments/assets/9db78c88-ca6d-4a26-bd68-986ef6009989)

![WhatsApp Image 2024-11-04 at 23 37 43_686f79af](https://github.com/user-attachments/assets/c985d9f9-2344-4252-8dd0-6aeed630cf2c)

![WhatsApp Image 2024-11-04 at 23 37 56_c2e01618](https://github.com/user-attachments/assets/3c90c363-3581-45f0-b664-b3903b42773d)

![WhatsApp Image 2024-11-04 at 23 38 07_b2bc71eb](https://github.com/user-attachments/assets/ce55f44d-aa86-4475-be5b-5d6957b52dad)





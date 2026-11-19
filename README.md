# Hybrid-Career-Path-and-Job-Recommendation-System-using-Sentence-BERT-and-Random-Forest
📌 Project Overview

The Hybrid Career Path and Job Recommendation System is an intelligent career guidance and job recommendation platform that helps candidates identify suitable career opportunities based on their educational qualifications, technical skills, work experience, certifications, projects, and interests.

The system combines Natural Language Processing (NLP), Sentence-BERT (SBERT), Machine Learning, and skill-gap analysis to provide personalized job recommendations, identify missing skills, suggest relevant courses, and guide candidates toward suitable career paths.

Unlike traditional keyword-based job recommendation systems, this project uses semantic similarity to understand the relationship between candidate profiles and job descriptions.

🎯 Objectives

Analyze resumes and extract relevant candidate information.

Identify technical skills, education, experience, certifications, and projects.

Recommend suitable job roles using semantic similarity.

Predict and rank relevant career opportunities using a hybrid recommendation approach.

Identify skill gaps between candidates and target job roles.

Recommend courses to improve missing skills.

Provide career guidance for both freshers and experienced professionals.

Improve recommendation relevance through candidate assessments and seniority-based filtering.

🛠️ Technologies Used

Category

Technologies

Programming Language

Python

Frontend / UI

Streamlit

NLP

Sentence-BERT (SBERT)

Machine Learning

Random Forest

Text Similarity

Cosine Similarity

Deep Learning / NLP Library

Sentence Transformers

Data Processing

Pandas, NumPy

Resume Processing

PDF and DOCX extraction

Job Dataset

O*NET and Technology Job Dataset

Course Recommendation

Skill-Gap Analysis

🏗️ System Architecture

The system follows a hybrid recommendation architecture.

Workflow

Candidate Input

Upload resume (PDF/DOCX).

Alternatively, enter profile details manually.

Resume Parsing

Extract education, skills, experience, certifications, and projects.

Process and clean extracted text.

Resume Quality Assessment

Evaluate resume completeness and quality.

Route candidates with insufficient information through the appropriate assessment process.

Skill Assessment

Conduct a core skills assessment.

Provide track-specific assessments based on selected career domains.

Semantic Matching

Generate text embeddings using Sentence-BERT.

Calculate semantic similarity between candidate profiles and job descriptions using cosine similarity.

Hybrid Recommendation

Use Random Forest for recommendation reranking.

Combine semantic relevance and candidate-related features.

Apply seniority constraints to improve job suitability.

Skill-Gap Analysis

Compare candidate skills with required job skills.

Identify missing and relevant skills.

Course Recommendation

Recommend courses based on identified skill gaps.

Career Guidance

Display recommended job roles.

Provide career progression suggestions and relevant job opportunities.

✨ Key Features

1. Resume Analysis

Supports PDF and DOCX resumes.

Extracts relevant candidate information.

Identifies skills, qualifications, experience, and projects.

2. Intelligent Job Recommendation

Uses Sentence-BERT embeddings.

Applies cosine similarity for semantic matching.

Provides ranked job recommendations.

3. Hybrid Recommendation Model

Integrates SBERT-based semantic matching with Random Forest.

Improves job ranking using additional candidate-related features.

Applies seniority-based filtering.

4. Resume Quality Assessment

Evaluates resume quality.

Identifies incomplete or insufficient candidate profiles.

Helps determine whether additional assessment is required.

5. Skill Assessment

Core skills assessment.

Career-track-specific assessments.

Supports different technology domains.

6. Skill-Gap Analysis

Identifies missing skills.

Compares existing candidate skills against job requirements.

7. Course Recommendation

Suggests relevant learning resources.

Recommends courses based on identified skill gaps.

8. Career Progression

Provides suitable career paths.

Helps candidates understand potential career growth opportunities.

💼 Supported Career Tracks

The system supports six major career domains:

Track

Career Opportunities

Data

Data Analyst, Data Scientist

Python Development

Python Developer

Java Development

Java Developer

Web Development

Web Developer

Backend Development

Backend Developer

Cloud & DevOps

Cloud Engineer, DevOps Engineer

🤖 Machine Learning Approach

Phase 1: SBERT-Based Recommendation

The baseline system uses Sentence-BERT to convert resume information and job descriptions into semantic embeddings.

Cosine similarity is used to measure the relevance between candidate profiles and available job opportunities.

Main components:

Text preprocessing

Resume and job-description embeddings

Semantic similarity calculation

O*NET-based occupation matching

Top-5 job recommendations

Phase 2: Hybrid Recommendation

The enhanced system introduces Random Forest as a reranking component.

The hybrid approach combines:

SBERT semantic similarity.

Candidate and job-related features.

Random Forest-based relevance prediction.

Skill matching and seniority constraints.

This helps improve the relevance of recommended job opportunities.

📂 Dataset Information

The project uses multiple datasets for job matching and course recommendation.

1. O*NET Database

Occupational information.

Job descriptions and occupation details.

Skills and knowledge requirements.

Career-related information.

2. Technology Job Dataset

Job titles.

Job descriptions.

Technical skills.

Industry information.

Approximately 12,945 cleaned technology job records were used in the processed dataset.

3. Course Dataset

Course titles.

Course descriptions.

Learning-related information.

Approximately 1,863 cleaned course records.

Dataset files may need to be downloaded separately. Original datasets are not necessarily included in this repository.

📈 Expected Output

The application provides:

Extracted candidate profile information.

Resume quality assessment.

Core and career-track assessment results.

Recommended job roles.

Job relevance scores.

Skill-gap identification.

Recommended learning courses.

Career progression guidance.

🔮 Future Enhancements

Integration with live job portals and APIs.

Support for additional career domains.

Improved multilingual resume processing.

Advanced explainable AI techniques.

Continuous model improvement using larger job datasets.

Personalized career roadmaps.

👩‍💻 Author

Srinithi Nivashini K.

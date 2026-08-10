# Employee Wellness Management Analytics

## Milestone 4 – Final Integration, Testing & Enhancement

### Project Overview

Employee Wellness Management Analytics is an AI-powered employee wellness
application designed to analyze employee text, identify emotions and
sentiment, provide personalized wellness recommendations, and maintain
employee wellness history.

The MoodMentor application integrates frontend, backend, NLP/ML models,
authentication, PostgreSQL database, recommendation features, and wellness
analytics into a single system.

---

## Project Objective

The main objective of this project is to develop an integrated Employee
Wellness Management System that can:

- Analyze employee text and detect emotions.
- Perform sentiment analysis.
- Provide personalized wellness recommendations.
- Maintain employee journal entries and wellness history.
- Provide an interactive wellness dashboard.
- Support secure user authentication.
- Store user and analysis information in PostgreSQL.
- Provide an AI-powered wellness chatbot.
- Support multilingual text processing.

---

## System Workflow

```text
User Input
    ↓
Text Preprocessing
    ↓
Language Detection
    ↓
Translation / Lemmatization
    ↓
Sentiment Analysis
    ↓
Emotion Detection
    ↓
Recommendation
    ↓
Database Storage
    ↓
Dashboard / Wellness History

## Technologies Used

### Frontend
- Streamlit
- Python
- Plotly

### Backend
- Python
- FastAPI
- PostgreSQL
- Psycopg2

### Authentication
- JWT Authentication
- Password Hashing
- OTP-based Email Verification
- Gmail SMTP

### NLP & Machine Learning
- Hugging Face Transformers
- BERT
- Qwen
- VADER Sentiment Analysis
- spaCy
- Language Detection
- Translation
- Lemmatization

### Database
- PostgreSQL
- Neon PostgreSQL

---

## Models Used

### BERT
Used for emotion detection and classification from employee text.

### Qwen
Used for the AI wellness chatbot and conversational wellness support.

### VADER
Used for sentiment analysis to identify positive, negative and neutral
sentiment.

---

## Main Features

- Secure user registration and login
- OTP-based verification
- Forgot password functionality
- JWT-based authentication
- Employee text analysis
- Emotion detection
- Sentiment analysis
- Personalized wellness recommendations
- Journal entries
- AI wellness chatbot
- Wellness history
- Interactive dashboard
- Emotion and sentiment visualizations
- PostgreSQL database integration
- Multilingual text processing
- CSV export
- PDF report generation

---

## Project Structure

```text
Employee-Wellness-Management-Analytics/

── Milestone4/
   ── Backend/
      ── auth.py
     ── backend.py
     ── db.py
      ── email_utils.py
     ── nlp_pipeline.py
   
   ── frontend/
      ── app.py
   
   ── Models/
     ── ModelsUsed.txt
   
   ── Screenshots/
       ── Dashboard1.png
       ── Emotion detection.png
       ── Home-page.png
       ── Journal entry.png
       ── Journal-recommendation.png
       ── Login-page.png
Screenshots
Login Page

Home Page

Dashboard

Journal Entry

Journal Recommendation

Emotion Detection

Testing

The application was tested for:

User registration
Login and authentication
OTP verification
Forgot password
Text input
Emotion detection
Sentiment analysis
Journal entries
Recommendations
Database operations
Dashboard functionality
Invalid and empty inputs
Multilingual inputs
Security

Sensitive information such as database credentials, SMTP credentials,
JWT secrets and API keys are stored securely using environment variables
and are not included in the repository.

Milestone 4

Milestone 4 focuses on final system integration, functional testing,
dashboard enhancement, recommendation validation, bug fixing and
final project organization.

The complete application integrates the frontend, backend, NLP/ML
pipeline, recommendation system, authentication and PostgreSQL database
into a unified Employee Wellness Management Analytics system.

Conclusion

The Employee Wellness Management Analytics project provides an
AI-powered platform for employee wellness analysis by combining
emotion detection, sentiment analysis, personalized recommendations,
journaling, chatbot support and wellness analytics.

The system follows the complete workflow from employee text input to
analysis, recommendation, database storage and visualization through
the wellness dashboard.




# Smart India Hackathon Workshop
# Date:07-03-2025
# Register Number:212224040257
# Name:RABI BASKAR PRABURAJAN
# Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
# Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

# Problem Creater's Organization
Ministry of Defence

# Idea

## 1.AI-Powered Question Generation

Generates dynamic, domain-specific questions based on the candidate's expertise.
Categorizes questions into ice-breaking, technical, and managerial levels.
Uses Knowledge Graphs and NLP models to ensure question relevance.
## 2.Automated Candidate Response Evaluation

AI analyzes candidate answers using Natural Language Processing (NLP).
Evaluates relevance, technical depth, and logical reasoning in responses.
Provides real-time scoring for objective assessment.

## 3.nterviewer Assistance & Feedback

AI suggests follow-up questions based on candidate responses.
Helps interviewers maintain fair and standardized evaluations.
Offers real-time feedback on question quality & candidate engagement.
Speech-to-Text & Sentiment Analysis

Converts spoken responses into text for analysis.
Sentiment analysis helps evaluate confidence, tone, and communication skills.

## 4.AI-Based Scoring System

Assigns relevancy scores to questions and responses.
Calculates an overall subject knowledge score for each candidate.
Generates comparative ranking of candidates based on scores.

## 5.Customizable Interview Experience

Allows interviewers to manually add/edit questions while maintaining AI suggestions.
Supports panel-based and one-on-one interviews.
Integrates with video conferencing tools for seamless remote interviews.

## 6.Comprehensive Reporting & Analytics

Generates detailed candidate performance reports with strengths & weaknesses.
Provides real-time dashboards for interviewers and HR teams.
Stores historical interview data for trend analysis & decision-making.

# Proposed Solution / Architecture Diagram

![image](https://github.com/user-attachments/assets/121abe52-b4ae-4400-9d3a-59455dd4c170)


# Use Cases

![image](https://github.com/user-attachments/assets/51ab7f06-707c-4520-80ed-25490249f300)


# Technology Stack

## Frontend:
React.js / Angular / Vue.js → For a modern, responsive web interface.
Tailwind CSS / Material UI → For a clean and structured UI/UX.
WebRTC / Zoom SDK / Jitsi → For video conferencing integration.

## Backend:
Python (FastAPI / Django / Flask) → For handling API requests and business logic.
Node.js (Express.js) → For real-time data processing (optional).
GraphQL / REST APIs → For structured data communication.

## AI/NLP Models:
OpenAI GPT / BERT / T5 → For dynamic question generation.
spaCy / NLTK → For text processing & NLP tasks.
Hugging Face Transformers → For response evaluation and scoring.
Google Speech-to-Text / OpenAI Whisper → For speech-to-text conversion.
VADER / TextBlob → For sentiment analysis of candidate responses.

## Database & Storage:
PostgreSQL / MySQL → For structured candidate/interview data storage.
MongoDB / Firebase → For unstructured and semi-structured data.
AWS S3 / Google Cloud Storage → For storing interview transcripts and video recordings.

## Authentication & Security:
OAuth2 / SAML / JWT → For secure user authentication.
Role-Based Access Control (RBAC) → To restrict permissions based on user roles.
End-to-End Encryption (E2EE) → For secure video and data transmission.

## Cloud & DevOps:
AWS / Azure / Google Cloud → For cloud hosting and scalability.
Docker / Kubernetes → For containerization and microservices deployment.
Prometheus / Grafana → For system monitoring and analytics.


# Dependencies

## AI & NLP Dependencies:
transformers → For pre-trained AI models (GPT, BERT, T5).
spaCy / nltk → For NLP and text processing.
speechrecognition / whisper → For speech-to-text processing.
scikit-learn / tensorflow / pytorch → For ML-based scoring models.

## Backend Dependencies:
FastAPI / Django / Flask → For backend API development.
SQLAlchemy → For database ORM.
Celery + Redis → For background task processing.

## Frontend Dependencies:
React.js / Angular / Vue.js → For building dynamic UI.
Axios / GraphQL Client → For API calls.
Tailwind CSS / Material UI → For frontend styling.

## Security Dependencies:
bcrypt / argon2 → For password hashing.
jwt → For authentication.
helmet / cors → For securing HTTP headers and cross-origin requests.

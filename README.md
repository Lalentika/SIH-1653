## Smart India Hackathon Workshop
# Date: 21.03.2025
## Register Number: 212224220052
## Name: Lalentika Twisha M
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1. Candidate Profile Management:
Maintain a profile for each candidate, including their area of expertise, years of experience, and the advertised post they applied for.
2. Question Bank Management:
Create a dynamic question bank categorized by: Basic Questions, Technical Questions, Managerial Questions (if the position requires managerial skills).
Each question should be tagged with the relevant expertise area and difficulty level (beginner, intermediate, advanced).
3. Candidate Response Evaluation:
Use Natural Language Processing (NLP) or Machine Learning (ML) techniques to evaluate the relevance of a candidate’s response to the question.
4. User Interface (UI) for Interviewers:
Provide the interviewer with an interface to ask questions, with automatic suggestions based on the candidate’s profile.
5. Response scoring:
Relevancy score of the response is determined based on how well it matches the expected answer.
Assign points to the response based on its relevance (e.g., 0-10 scale).
6. Use Adaptive Questioning:
The next question can be chosen based on the candidate’s response and the previous questions’ relevancy scores.
7. Question Relevancy:
Questions can be ranked by how closely they align with the candidate’s field of expertise. This can be done manually or with an automated algorithm that uses the candidate's skills/experience.
8. Response Relevancy (Using NLP/ML):
Use models like BERT or GPT to analyze candidate responses and score them based on: Lexical matching, Contextual analysis, Scoring Mechanism.
9. Feedback System:
Provide a feedback mechanism for both the interviewer and the candidate.
10. Candidate Suitability Report:
After the interview, generate a detailed suitability report for each candidate, including:
-A breakdown of question and response relevancy scores.
-Final suitability assessment based on the overall score.
-Suggestions for areas of improvement (if applicable).

## Proposed Solution / Architecture Diagram

![image](https://github.com/user-attachments/assets/88745b95-7790-4dfe-b689-d3d9d9012eda)


## Use Cases

![image](https://github.com/user-attachments/assets/3642fd44-73e2-4b38-83e7-c5647cc7e29f)

## Technology Stack

1. Frontend: React.js / Angular.js
2. Backend: Node.js / Express.js
3. Database: MongoDB / PostgreSQL
4. Authentication: OAuth 2.0 / JWT for secure user identity management
5. Voice Processing: Coqui TTS or other TTS tools for voice synthesis in simulations
6. Deployment: Docker for containerization, Kubernetes for scalability

## Dependencies
1.react-router-dom → For navigation in React

2.axios → For handling API requests

3.socket.io-client → For real-time communication

4.tailwindcss → For styling the UI

5.chart.js → For interview performance graphs

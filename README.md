# Smart India Hackathon Workshop
# Date:14.03.2025
## Register Number:212224040298
## Name:k saranya
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

The image shows a problem statement for a Smart India Hackathon (SIH) project. The task is to create a "Web-based Selector-Applicant Simulation Software" for the Ministry of Defence (Recruitment and Assessment Centre).

Key Points from the Problem Description:

1. Goal: Develop a simulation-based platform to evaluate applicants' responses and match them with the required expertise.


2. Challenges:

Objectively assessing candidate responses.

Ensuring relevance of answers to the question.

Providing a realistic interview experience.



3. Expected Outcome:

Real-life Board Room experience with initial tie-breaking questions.

Provide a quantifiable score for experts and candidates.

Grade responses for relevance and subject knowledge.

Arrive at an overall score for suitability against the advertised post.
## Proposed Solution / Architecture diagram
![WhatsApp Image 2025-03-14 at 12 54 25_17ed2b56](https://github.com/user-attachments/assets/15d820aa-55e8-4a10-8b89-5ed1fcc8334e)


## Use Cases
Here are some key use cases for the Web-based Selector-Applicant Simulation Software:


---

1. Candidate Registration and Login

Description:

A candidate should be able to register with personal details (name, email, qualifications, etc.).

After registration, the candidate should be able to log in using secure authentication (OAuth, JWT).


Actors:

Candidate

System


Flow:

1. Candidate provides login credentials.


2. System validates the credentials.


3. If valid, the candidate is logged in.


4. If invalid, an error message is shown.




---

2. Expert Registration and Login

Description:

An expert (interviewer) should be able to register and log in securely.

Experts should have role-based access to view and score responses.


Actors:

Expert

System


Flow:

1. Expert provides login details.


2. System verifies credentials.


3. On successful login, expert gains access to the dashboard.




---

3. Start a Simulation (Candidate)

Description:

A candidate should be able to start a simulation based on job role and difficulty level.

Questions should be selected from a dynamic question bank.


Actors:

Candidate

System


Flow:

1. Candidate selects job role and level.


2. System loads relevant questions.


3. Timer starts, and candidate begins answering.




---

4. Real-Time Evaluation and Feedback

Description:

System should evaluate candidate responses in real-time using NLP and ML.

Provide hints or guidance if configured.


Actors:

Candidate

System


Flow:

1. Candidate submits an answer.


2. System evaluates the answer for relevance and correctness.


3. Feedback is shown (if enabled).




---

5. Scoring and Ranking

Description:

System should calculate a score based on relevance, depth, and correctness of answers.

Rank candidates based on overall performance.


Actors:

System


Flow:

1. System evaluates the answers.


2. Assigns a score for each question.


3. Calculates an overall

## Technology Stack

Here’s a suggested technology stack 

1. Frontend (Client Layer)

Framework:

React.js / Angular / Vue.js


Languages:

HTML, CSS, JavaScript, TypeScript


UI Libraries:

Material-UI, Bootstrap, Tailwind CSS


State Management:

Redux, Context API, Vuex

2. Backend (Application Layer)

Framework:

Node.js (Express) / Django (Python) / Flask (Python) / Spring Boot (Java)


Languages:

JavaScript (Node.js), Python, Java, or Kotlin


API Handling:

RESTful API / GraphQL


Authentication:

OAuth 2.0, JWT
3. Database (Database Layer)

Relational Database:

PostgreSQL / MySQL


NoSQL Database:

MongoDB (for flexibility in storing structured and unstructured data)


Caching:

Redis


4. AIML Layer

Machine Learning Frameworks:

TensorFlow, PyTorch, Scikit-learn


Natural Language Processing (NLP):

spaCy, NLTK, OpenAI API


Recommendation System:

Collaborative Filtering, Content-Based Filtering

5. Infrastructure Layer

Cloud Hosting:

AWS (EC2, S
## Dependencies
Here are the key dependencies for developing the Web-based Selector-Applicant Simulation Software:


---

1. Frontend Dependencies

Frameworks/Libraries:

React.js – react, react-dom

Angular – @angular/core, @angular/router

Vue.js – vue, vue-router


State Management:

Redux – redux, react-redux

Vuex – vuex

Context API – Built-in with React


UI Components:

Material-UI – @mui/material

Bootstrap – bootstrap

Tailwind CSS – tailwindcss


HTTP Requests:

Axios – axios

Fetch API – Built-in with browsers


Form Handling:

Formik – formik

React Hook Form – react-hook-form


Routing:

React Router – react-router-dom

Vue Router – vue-router


Testing:

Jest – jest, @testing-library/react

Cypress – cypress



---

2. Backend Dependencies

Frameworks:

Node.js – express

Django – django, djangorestframework

Flask – flask

Spring Boot – spring-boot-starter-web


Authentication:

OAuth – passport, django-allauth

JWT – jsonwebtoken, djangorestframework-jwt


Database Connection:

MongoDB – mongoose

MySQL/PostgreSQL – sequelize, mysql, pg


Security:

Helmet.js – helmet

CORS – cors


Validation:

Joi – joi

Express Validator – express-validator


File Upload:

Multer – multer


Real-Time Communication:

Socket.IO – socket.io



---

3. AI/ML Dependencies

Machine Learning:

TensorFlow.js – @tensorflow/tfjs

Scikit-learn – scikit-learn

PyTorch – torch


NLP:

spaCy – spacy

NLTK – nltk

Transformers (HuggingFace) – transformers


Recommendation System:

Surprise – scikit-surprise



---

4. Database Dependencies

Relational:

PostgreSQL – pg, sequelize

MySQL – mysql, mysql2


NoSQL:

MongoDB – mongoose


Caching:

Redis – redis, ioredis



---

5. Infrastructure Dependencies

Cloud Services:

AWS SDK – aws-sdk

Google Cloud SDK – @google-cloud/storage

Azure SDK – @azure/storage-blob


Containerization:

Docker – docker, docker-compose

Kubernetes – kubernetes-client

# Course-Recommendation-System

# AI-Based Course Recommendation System

## Project Overview

The **AI-Based Course Recommendation System** is designed to help users discover suitable online courses based on their **interests, skill levels, and learning goals**.

With thousands of online courses available today, it can be difficult for learners to choose the right one. This system simplifies the process by analyzing user preferences and recommending the most relevant courses from a dataset.

The project combines **data filtering techniques and an AI language model** to provide personalized recommendations along with explanations.

---

## Project Objectives

- Recommend courses based on user interests
- Filter course data using Python
- Provide AI-generated explanations for recommended courses
- Build a simple user interface for interaction
- Demonstrate the use of recommendation systems in education

---

## Technologies Used

- Python
- Streamlit (Frontend)
- Pandas
- NumPy
- Ollama
- Phi-3 AI Model
- CSV Dataset
- GitHub

---

## Project Architecture

The system follows a modular pipeline where each component performs a specific function.

User
↓
Frontend Interface
↓
Recommendation Engine
↓
AI Explanation Module
↓
Recommended Courses


---

## Project Structure
course-recommendation-system/

│
├── frontend/
│ └── app.py
│
├── dataset/
│ └── courses.csv
│
├── recommendation_engine/
│ └── recommender.py
│
├── ai_module/
│ └── ai_recommender.py
│
├── requirements.txt
│
└── README.md


---

## Module Description

### Frontend Module

**File:** `frontend/app.py`

Responsibilities:
- Collect user input
- Allow users to select interests and skill level
- Send data to the recommendation engine
- Display recommended courses and AI explanations

---

### Dataset Module

**File:** `dataset/courses.csv`

The dataset stores information about available courses.

Example fields:

- Course_Name
- Category
- Level
- Rating
- Platform

Example data:

| Course Name | Category | Level | Rating | Platform |
|--------------|-----------|-------|--------|-----------|
| Python for Beginners | Programming | Beginner | 4.5 | Coursera |
| Machine Learning Basics | AI | Intermediate | 4.7 | Udemy |
| AI for Everyone | AI | Beginner | 4.6 | Coursera |

---

### Recommendation Engine

**File:** `recommendation_engine/recommender.py`

Responsibilities:

- Load the dataset
- Process user preferences
- Filter courses based on interest and level
- Rank courses based on rating
- Return top recommendations

The recommendation method used is **Content-Based Filtering**.

---

### AI Module

**File:** `ai_module/ai_recommender.py`

Responsibilities:

- Receive recommended courses
- Use an AI language model to generate explanations
- Provide personalized course descriptions

The AI model runs locally using **Ollama**.

---

## System Workflow

1. The user opens the application.
2. The user selects their **interest** and **skill level**.
3. The frontend collects the input.
4. The recommendation engine filters courses from the dataset.
5. Top courses are selected based on relevance and rating.
6. The AI module generates explanations.
7. Recommended courses and explanations are displayed.

---

## Team Responsibilities

### Member 1 – Frontend Developer

Responsibilities:
- Design the user interface
- Collect user input
- Display recommendations

Files handled:

frontend/app.py

---

### Member 2 – Recommendation Engine Developer

Responsibilities:
- Create and maintain dataset
- Implement filtering logic
- Develop recommendation algorithm

Files handled:
dataset/courses.csv
recommendation_engine/recommender.py

---

### Member 3 – AI Integration Developer

Responsibilities:
- Install and configure AI model
- Integrate AI with Python
- Generate explanations for recommended courses

Files handled:
ai_module/ai_recommender.py

---

## Installation

Clone the repository:

git clone https://github.com/yourusername/course-recommendation-system.git

Navigate to the project folder:
cd course-recommendation-system

Install required libraries:
pip install -r requirements.txt

Run the application:
streamlit run frontend/app.py


---

## Future Improvements

Possible improvements include:

- Implement collaborative filtering algorithms
- Integrate real online course APIs
- Add user login and history tracking
- Improve AI recommendations
- Create a chatbot-based course advisor

---

## Conclusion

The **AI-Based Course Recommendation System** demonstrates how recommendation algorithms and AI models can work together to help users find relevant educational resources.

This project highlights the practical application of **data filtering, machine learning concepts, and AI-driven explanations** in the field of online education.

# AI-Based Course Recommendation System

## Overview
This project is a machine learning-based system that recommends personalized online courses based on user interests, skill level, and learning goals.

It uses content-based filtering techniques to analyze user preferences and match them with relevant courses from a dataset. Additionally, an AI language model is integrated to generate meaningful explanations for each recommendation, improving user understanding and decision-making.

## Technologies Used
- Python
- Scikit-learn
- Pandas, NumPy
- Streamlit
- Ollama (Phi-3 AI Model)

## Features
- Personalized course recommendations  
- Content-based filtering using similarity techniques  
- AI-generated explanations for recommended courses  
- Interactive user interface using Streamlit  

## Project Structure
course-recommendation-system/
- frontend/ (Streamlit app)
- dataset/ (courses dataset)
- recommendation_engine/ (filtering logic)
- ai_module/ (AI-based explanation)

## How It Works
1. User selects interests and skill level  
2. System processes input and applies content-based filtering  
3. Courses are ranked using similarity metrics (e.g., cosine similarity) and ratings  
4. AI module generates explanations for each recommendation  

## Future Improvements
- Add collaborative filtering  
- Integrate real-world APIs  
- Improve recommendation accuracy  
- Deploy as a full web application  

## Conclusion
This project demonstrates the practical application of machine learning and AI in building intelligent recommendation systems for education.

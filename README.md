
# AI-Powered Language Learning Chatbot

## Overview
The AI-powered language learning chatbot is designed to help users improve their language skills through interactive conversations. By leveraging the Google Gemini API and AI-driven feedback, the chatbot provides personalized guidance, corrects mistakes, and enhances the learning experience. It is developed as a Flask web application with an interactive UI, allowing users to engage in a real-life chatbot experience.

## Features
### 1. Conversational Chatbot
- Asks users about their language learning preferences.
- Engages in meaningful dialogues in the target language.
- Provides structured learning experiences through AI-driven interactions.

### 2. Speech Output
- Uses Google Text-to-Speech (gTTS) to convert responses into speech.
- Supports adjustable speech speed (normal/slow).
- Enhances engagement with voice-based responses.

### 3. Mistake Analysis & Correction
- Analyzes grammar and vocabulary mistakes.
- Stores mistakes and corrections in an SQLite database.
- Uses retrieval techniques to ensure mistake tracking accuracy.

### 4. Personalized Feedback System
- Summarizes users' mistakes for review.
- Provides categorized feedback with grammar explanations and learning resources.
- Suggests structured exercises for improvement.

### 5. Flask Web Application with Interactive UI
- A fully functional chatbot interface built using HTML, CSS, and JavaScript.
- Users can input messages, receive responses, and interact via a real-life chatbot UI.
- Includes buttons for checking mistakes, receiving feedback, and activating speech output.

## Technologies Used
- **Backend:** Python with Flask
- **AI Processing:** Google Generative AI (Gemini API)
- **Speech Synthesis:** Google Text-to-Speech (gTTS)
- **Translation:** Deep Translator
- **Database:** SQLite for storing and analyzing user mistakes
- **AI Management:** LangChain for LLM-based responses and retrieval
- **Frontend UI:** HTML, CSS, JavaScript, jQuery

## System Workflow
1. User selects a learning language and proficiency level.
2. Chatbot generates responses using Google Generative AI (Gemini API) and provides real-time speech output.
3. User mistakes are analyzed, and corrections are stored in SQLite.
4. Personalized feedback is generated based on past mistakes.
5. Users review corrections and practice improved language usage.
6. The UI facilitates seamless interaction between the user and the chatbot.

## Database Structure
The chatbot maintains a database (`mistakes.db`) with a table to store:
- User input
- Identified mistakes
- Corrected responses
- Learning progress

## Future Enhancements
- **Multilingual Support:** Expand to more languages and dialects.
- **Advanced Speech Recognition:** Improve speech-to-text accuracy.
- **Gamification:** Introduce achievements and rewards for engagement.
- **Integration with Learning Apps:** Sync progress with language-learning platforms.
- **Voice-based Conversation Handling:** Allow users to interact via voice commands.
- **Improved UI Design:** Enhance the chatbot interface with animations and better visuals.

## Conclusion
The AI-powered chatbot integrates LLMs, speech synthesis, and mistake analysis to create a dynamic language learning experience. By providing corrections and personalized feedback, it helps learners improve their skills effectively. The integration of Flask with an interactive UI makes the chatbot engaging and immersive. Future updates will further enhance its usability and user engagement.

## Output Links
![image](https://github.com/user-attachments/assets/e8b981fa-9dce-4cdc-9e0e-c950ededd3bd)
 
 
![image](https://github.com/user-attachments/assets/c98183d3-a404-43b1-aad8-fa458a0ee8b2)
![image](https://github.com/user-attachments/assets/a4dd9740-4950-4953-8750-80c40403c977)

- **Audio File:** [Click Here](https://drive.google.com/file/d/1yihuAoiYGx6ZiX4pWmQLl8Q5hBPC0XNR/view?usp=sharing)
-

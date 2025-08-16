🏋️‍♂️ JIM BRO - Fitness & Diet AI Assistant


JIM BRO is a fun and interactive personal fitness and diet assistant powered by AI. Enter your details, select a goal, and get a personalized workout or diet plan instantly!

🧠 Project Description

Plan your fitness journey with AI assistance:

Collects user data: name, age, weight, height

Calculates BMI and suggests a suitable goal

Generates Workout or Diet Plans based on your goals

Designed for quick, actionable, and motivational guidance

✨ Features

AI-Powered Plans: Custom workout and diet recommendations

BMI-Based Goal Suggestion: Guides users to healthy targets

Interactive Wizard Interface: Step-by-step data entry

Fast & Responsive: Minimal wait with clean UI

Session Management: Keeps track of current progress

🧰 Technologies Used
Feature	Implementation
Backend	Python, Flask
Frontend	HTML, CSS, JavaScript
AI Integration	LLM API (configurable via .env)
Session Management	Flask sessions
Environment Variables	Python-dotenv
Styling	Modern gradient UI, responsive forms
🧱 Project Architecture
Backend

app.py → Initializes Flask application

routes/main.py → API endpoints (/api/ask, /api/check-goal)

services/gym_ai.py → Handles AI requests and responses

Frontend

templates/index.html → Wizard interface

static/style.css → Styling and theme

static/script.js → Handles UI interaction and API calls

Environment Variables (.env)

LLM_API_URL → AI endpoint

LLM_API_KEY → API key

LLM_MODEL → Model to use

LLM_TIMEOUT → API request timeout

SECRET_KEY → Flask session secret

🧩 How it Works

User Wizard: Collects user info and goal

Goal Validation: Suggests suitable goal based on BMI

Plan Generation: Sends user data to LLM API

Response: AI returns a detailed workout or diet plan

Display: Plan shown in the UI; repeat anytime

🎮 Getting Started
Requirements

Python 3.8+

Flask

Requests library

LLM API credentials

Run the App
git clone https://github.com/yourusername/jim-bro.git
cd jim-bro
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py


Open your browser at: http://localhost:5000

🏁 Conclusion

JIM BRO is a demonstration of:

Web development with Flask

Interactive multi-step forms

Integration with AI language models

Personalized fitness & diet guidance

Perfect for beginners and fitness enthusiasts looking for AI-powered recommendations.

🙏 Thank You

Stay fit and motivated! 💪

# 🏋️‍♂️ JIM BRO - Personalized Fitness & Diet Assistant



**JIM BRO** is an interactive **web-based fitness and diet assistant** powered by a Large Language Model (LLM). The AI provides **personalized workout and diet plans** based on user inputs like age, weight, height, and fitness goals. It’s designed to motivate users and optimize fitness routines with **BMI-based goal suggestions**.

---

## 🧠 Project Description

The app guides users through a multi-step wizard:

1. Enter basic details: **name, age, weight, height**
2. Select your **fitness goal**: Bulk, Cut, or Maintain
3. AI suggests your **ideal plan** based on BMI
4. Generate either a **Workout Plan** or **Diet Plan**

The AI responds **directly with detailed plans**, without small talk.

---

## ✨ Features

- **Personalized Workout & Diet Plans:** AI-generated plans tailored to your body stats and goals.
- **BMI-Based Goal Suggestions:** Ensures realistic and healthy fitness goals.
- **Interactive Wizard Interface:** Step-by-step guided input.
- **LLM Integration:** Powered by a language model for natural, detailed responses.
- **Responsive Design:** Modern and clean UI for easy interaction.

---

## 🧰 Technologies Used

| Feature               | Implementation                                      |
|-----------------------|----------------------------------------------------|
| Backend               | Python, Flask                                      |
| Frontend              | HTML, CSS, JavaScript                              |
| AI Integration        | LLM API (configurable via .env)                   |
| Session Management    | Flask sessions                                     |
| Environment Variables | Python-dotenv                                     |
| Styling               | Modern gradient UI, responsive forms              |

---

## 🧱 Architecture

### Backend
- **app.py**: Flask app initialization
- **routes/main.py**: API endpoints (`/api/ask`, `/api/check-goal`)
- **services/gym_ai.py**: Handles AI requests and responses

### Frontend
- **templates/index.html**: Multi-step wizard interface
- **static/style.css**: Styling and gradient theme
- **static/script.js**: Wizard logic, API calls, response handling

### Environment Variables
- `.env` file stores **API keys**, **model configuration**, and **secret keys**.

---

## 🧩 How it Works

1. **User Input Wizard**
   - Collects user info: name, age, weight, height, fitness goal
2. **Goal Check**
   - Calculates BMI and suggests the most suitable goal
3. **Plan Generation**
   - Sends a request to LLM API with user info
   - AI returns a **detailed plan**
4. **Display**
   - Plan is shown in a styled response area
   - Users can repeat the process anytime

---

## 🎮 Getting Started

### Requirements
- Python 3.8+
- Flask
- Requests library
- LLM API credentials


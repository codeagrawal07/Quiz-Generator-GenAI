# 🧠 AI Quiz Generator from a YouTube Video Summary (Gemini API)

This project uses Google’s **Gemini Pro (Generative AI)** to generate interactive quizzes from a summary of a YouTube video. By combining the power of **prompt engineering** and **structured output (JSON)**, this tool helps you auto-generate MCQs for learning or revision.

---

## 🚀 Features

- ✅ Accepts a summary of any YouTube educational video
- ✅ Automatically generates 3–5 multiple-choice questions (MCQs)
- ✅ Provides options and the correct answer
- ✅ Returns output in **JSON format** for easy integration into apps or UIs
- ✅ Ideal for e-learning platforms, teachers, and students

---

## 🛠 Tech Stack

- 🧠 **Google Generative AI (Gemini Pro)**
- 🐍 **Python 3.x**
- 📦 `google-generativeai`
- 📓 Jupyter Notebook / VS Code

---

## 📸 Sample Output (JSON)

```json
{
  "title": "Support Vector Machines",
  "quiz": [
    {
      "question": "What is the primary function of a Support Vector Machine?",
      "options": ["Clustering", "Classification", "Regression", "Dimensionality Reduction"],
      "answer": "Classification"
    },
    ...
  ]
}
```
# PROBLEM STATEMENT
## 🔧 "AI Quiz Generator from a YouTube Video Summary"
## 🧠 Project Goal:
Take a summary of a YouTube video (manually copied or fetched), and let the model generate:

- A title of the topic

- 3-5 quiz questions

- Each question with options and the correct answer

- Output in JSON format so it's easy to use in real apps

# 🛠️ Tools Used:
- Python

- google.generativeai (Gemini via genai)

- json module

- .ipynb for interactive use

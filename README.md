# 🤖 AI Tweet Generator using Reflex Agent

This mini project demonstrates a simple **AI Reflex Agent** that generates tweets based on user input using predefined rules. It uses basic Natural Language Processing (NLP) techniques without relying on deep learning or external AI APIs.

---

## 🧠 What is a Reflex Agent?

A **reflex agent** acts only on the basis of the **current percept**, ignoring the rest of the percept history. It follows condition-action rules, making decisions based on matching patterns, keywords, or specific rules.

In this project, a reflex agent uses basic logic to generate tweets by analyzing keywords or sentiment present in the input.

---

## 🚀 Features

- 🧠 Implements a basic AI **reflex agent** logic
- 📝 Accepts user input and returns auto-generated **tweet-style responses**
- 💬 Handles common input types such as greetings, motivation, complaints, etc.
- 🔄 Reusable function to continue generating tweets until user stops
- ✅ Beginner-friendly project to understand basic AI agent design

---

## 🛠️ How It Works

The agent processes the user input and:

1. Scans for keywords (like “happy”, “sad”, “hello”)
2. Matches the input to a set of predefined rules
3. Returns an appropriate tweet-style message

The code uses:
- `input()` for interactive prompts
- Basic `if-elif-else` conditions for decision making
- A `while` loop for continuous interaction until user exits

---

## 📌 Example Interaction

```text
You: I'm feeling sad today
AI Tweet: It's okay to feel down sometimes. Brighter days are coming! 💫

You: give me motivation
AI Tweet: Keep pushing forward, your goals are worth the effort! 🚀

You: exit
AI Tweet: Goodbye! Have a productive day! 👋
```

# 💡 Ideal For
Students exploring AI fundamentals

Demonstrating reflex agent behavior

Creating lightweight text-generation bots

Python beginners interested in rule-based NLP

---

# ✅ Requirements
Jupyter Notebook environment (or any Python 3 interpreter)

install google-generativeai and ipywidgets libraries required
```python
pip install google-generativeai
pip install ipywidgets
```
---

# 📜 License
This project is open-sourced under the MIT License — feel free to use, modify, and share it with proper credit.

---

# 🙌 Acknowledgments
Developed as a part of AI agent simulation studies under the mentorship of IBM SkillBuilds

---

# Author
Developed by Saksham Sharma under the IBM Skill Builds Learner to Builder: Become an AI Agent Architect Program

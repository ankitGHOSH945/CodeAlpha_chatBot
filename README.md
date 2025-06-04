````markdown
# 🤖 Basic Rule-Based Chatbot in Python

This is a simple, beginner-friendly **rule-based chatbot** built with Python. The chatbot uses `if-elif` conditions to respond to basic user inputs like greetings, questions, and farewells.

---

## 📌 Features

- Responds to greetings like "hello", "hi", "hey"
- Answers simple questions such as:
  - "How are you?"
  - "What's your name?"
  - "What time is it?"
  - "What can you do?"
- Says goodbye when you type "bye"
- Gives a fallback response when it doesn't understand
- Friendly and clean user interaction in the terminal

---

## 🚀 Getting Started

### ✅ Prerequisites
- Python 3.x installed on your system
- A terminal or code editor (like VS Code, PyCharm, etc.)

---

## 💻 How to Run the Chatbot

1. **Download or copy the `chatbot.py` file**
2. **Open terminal in the folder where the file is saved**
3. **Run the script**:

```bash
python chatbot.py
````

You will see:

```
🤖 Welcome to ChatBot!
💬 You can talk to me. Type 'bye' to exit.
```

Then start chatting by typing phrases like:

* `hello`
* `how are you`
* `what is your name`
* `thank you`
* `what time is it`
* `bye`

---

## 🧠 Example Chat

```text
You: hello
Bot: Hello there! 👋

You: how are you
Bot: I'm doing great, thanks for asking! 😊

You: what is your name
Bot: I'm a simple rule-based chatbot built with Python.

You: what time is it
Bot: The current time is 03:45 PM. ⏰

You: bye
Bot: Goodbye! Have a great day! 👋
```

---

## 🛠️ Code Concepts Used

* `if-elif` statements
* `while` loop for continuous conversation
* `input()` and `print()` for interaction
* `datetime` module to get current time
* Basic text matching using `.lower().strip()`

---

## 📄 File Structure

```
chatbot_project/
│
├── chatbot.py       # Main chatbot script
└── README.md        # Project documentation (this file)
```

---

## 👨‍💻 Author

**Ankit Ghosh**
Built as part of the CodeAlpha Python Internship – Task 4: Basic Chatbot

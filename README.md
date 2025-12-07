# Smart Learning Chatbot

A Python-Based, Self-Learning AI Chatbot Using JSON Storage

This project is a simple but extensible **self-learning chatbot** built with Python. It stores question–answer pairs in a JSON file and improves itself by learning new answers from the user when it encounters unknown questions.

---

## 🚀 Features

* 📁 **JSON-based knowledge storage**
* 🧠 **Self-learning system** (learns new answers from user input)
* 🔍 Fuzzy text matching using `difflib.get_close_matches`
* 💾 Automatically saves new knowledge permanently
* 🐍 Fully built with pure Python

---

## 📦 Technologies Used

* **Python 3.x**
* **JSON**
* **difflib** (for fuzzy matching)

---

## 📂 Project Structure

```
/smart-learning-chatbot
│
├── database.json
└── chatbot.py
```

---

## 🧩 How It Works

### 1. Loading the Database

The bot loads question–answer pairs from a JSON file.

### 2. Learning New Answers

If the bot doesn't know the answer, it asks the user to teach it and stores the answer permanently.

### 3. Fuzzy Matching

Uses `get_close_matches` to find the most similar known question.

---

## ▶️ Run the Project

Run the chatbot with:

```bash
python chatbot.py
```

---

## 📝 Example Interaction

**You:** Hello
**Bot:** Sorry, I don't know how to answer that. Would you like to teach me?

**You:** Hello means a greeting.
**Bot:** Thank you! I learned something new.

---

## 🔧 Future Improvements

* API integration
* GUI interface (PyQt5, Tkinter, etc.)
* More advanced search algorithms
* NLP-based answer generation

---

## 🤝 Contributing

Feel free to submit pull requests or suggestions for improvement.

---

## 📜 License

This project is released under the **MIT License**.

---

## ⭐ Support the Project

If you like this project, don't forget to ⭐ star the repository!

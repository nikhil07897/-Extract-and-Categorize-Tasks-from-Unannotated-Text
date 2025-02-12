# ✅ Task Extraction & Categorization from Unannotated Text

🚀 This project automatically **extracts and categorizes tasks** from unstructured text using **Natural Language Processing (NLP)**. It identifies **tasks, assignees, deadlines, and categories** to improve task management.

---

## ✨ Features
- **🔍 Task Extraction**: Detects task-related sentences from raw text.
- **📌 Categorization**: Groups tasks into relevant categories (e.g., development, cleaning, communication).
- **👤 Assignee Identification**: Extracts the person responsible for a task.
- **🕒 Deadline Detection**: Finds due dates like "by 5 PM today" or "before Thursday".
- **⚡ Uses NLP Techniques**: Built with `spaCy` & `NLTK` for text processing.

---

## 📂 Project Structure
```plaintext
📦 task-extraction
│── 📝 extract_and_categorize_tasks.py   # Main script
│── 📄 requirements.txt                  # Dependencies
│── 📜 README.md                          # Project Documentation
```

---

## 🔧 Installation

### 1️⃣ Clone the Repository:
```bash
git clone https://github.com/nikhil07897/task-extraction.git
cd task-extraction
```

### 2️⃣ Install Dependencies:
```bash
pip install -r requirements.txt
```

Or manually install:
```bash
pip install spacy nltk
python -m spacy download en_core_web_sm
```

---

## 🚀 How to Use

Run the script with:
```bash
python extract_and_categorize_tasks.py
```

### 📌 Example Input:
```plaintext
John must complete the report by 5 PM today.
Sarah needs to review the marketing materials before Thursday.
Please clean the conference room by 3:00 PM.
The team should implement the new feature by next week.
```

### 🔍 Extracted Output:
```plaintext
Task: "John must complete the report by 5 PM today."
Assignee: John
Deadline: 5 PM today
Category: Review

Task: "Sarah needs to review the marketing materials before Thursday."
Assignee: Sarah
Deadline: Before Thursday
Category: Review

Task: "Please clean the conference room by 3:00 PM."
Assignee: Not specified
Deadline: 3:00 PM
Category: Cleaning
```

---

## 🛠️ Technologies Used
- **Python** 🐍
- **spaCy** 🔍 (for Named Entity Recognition)
- **NLTK** 📖 (for sentence tokenization and stopword filtering)
- **Regex** 🔢 (for custom pattern extraction)

---

## 🏆 Key NLP Techniques Used
- **Tokenization**: Splitting text into words and sentences.
- **Named Entity Recognition (NER)**: Identifies names, dates, and times.
- **POS Tagging**: Identifies verbs and modal verbs to detect tasks.
- **Custom Keyword Matching**: Categorizes tasks into groups.

---

## 🌟 Future Enhancements
- 🔄 **Integrate with To-Do Apps** (Trello, Notion, etc.)
- 🎙 **Convert voice notes to tasks**
- 📊 **Task Priority Detection** based on urgency
- 🔍 **Better Deadline Parsing** using `dateparser`

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📜 License
This project is licensed under the **MIT License**.

---

### ✨ Created by [Nikhil](https://github.com/nikhil07897)
```

---

### 📌 What This README Includes:
✔️ Well-structured sections  
✔️ Clear **installation & usage** guide  
✔️ **Example output** for better understanding  
✔️ **Future enhancements** to improve engagement  


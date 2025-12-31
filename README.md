# 📧 Email Spam & Not-Spam Classifier using Flask and Machine Learning

This project is an **advanced Flask-based web application** that uses **Machine Learning** techniques to classify an email or message as **Spam** or **Not Spam**.

---

## 🚀 Key Features
- Web-based Email Classification System
- Detects **Spam and Not Spam (Ham)** messages
- Uses **Machine Learning Model**
- Fast and Accurate Prediction
- Simple UI with Flask
- Ready for College / Academic Submission

---

## 🛠️ Technologies Used
- Python 🐍
- Flask 🌐
- Scikit-learn 🤖
- HTML / CSS
- Pickle (for model loading)

---

## 📂 Project Structure
```
project/
│── app.py                 # Main Flask application
│── models/
│   ├── cv.pkl             # CountVectorizer (Text → Numbers)
│   ├── clf.pkl            # Trained ML Classifier Model
│── templates/
│   └── index.html         # Frontend HTML file
│── README.md              # Project Documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Install Required Libraries
```bash
pip install flask scikit-learn
```

---

### 2️⃣ Run the Application
```bash
python app.py
```

---

### 3️⃣ Open in Browser
```
http://localhost:8080
```

---

## 🧠 How the System Works (Process Flow)

### Step 1: User Input
- User enters an **Email / Message** in the input box.

### Step 2: Text Preprocessing
- The entered text is converted into **numerical format** using **CountVectorizer**.

### Step 3: Model Prediction
- The trained Machine Learning model analyzes the input.

### Step 4: Classification Output
- `1` → Spam ❌
- `0` → Not Spam ✅

### Step 5: Result Display
- The result is shown on the web page.

---

## 🧪 Example Test Cases

### Example 1: Spam Message
**Input:**
```
Congratulations! You have won a free lottery ticket. Click now!
```
**Output:**
```
Spam ❌
```

---

### Example 2: Not Spam Message
**Input:**
```
Hi, please find the attached project report for tomorrow's meeting.
```
**Output:**
```
Not Spam ✅
```

---

## 🧠 Machine Learning Model Details
- Algorithm: Naive Bayes / Logistic Regression
- Vectorization Technique: CountVectorizer
- Input Type: Text (Email Content)
- Output Classes:
  - `1` → Spam
  - `0` → Not Spam

---

## 🔐 Advanced Features (Extendable)
- Can be upgraded to **TF-IDF Vectorizer**
- Can add **Email Dataset Training**
- Can be deployed on **Heroku / Render**
- Can include **Login System**
- Can store results in **Database**

---

## 🎓 Academic Use
This project is suitable for:
- Mini Project
- Final Year Project (Basic Level)
- Machine Learning Practical
- Flask Web Development Assignment

---

## 👤 Author

**Himanshu Patle**  

[![Instagram](https://img.shields.io/badge/Instagram-000000?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/h_imanshu_01/?next=%2F)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-patle-2b563730b/)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/imanshu-01)

---

## 📜 License
This project is intended for **Educational Purposes Only**.

---

## ❤️ Acknowledgement
Special thanks to Flask and Scikit-learn communities.

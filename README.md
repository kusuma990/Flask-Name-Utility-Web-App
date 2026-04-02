# Flask-Name-Utility-Web-App
# 🚀 Flask Name Utility Web App

A simple and beginner-friendly web application built using Flask that performs different operations on a user-provided name via URL query parameters.

---

## 📌 Features

This app provides multiple functionalities:

* 🔤 Convert name to **UPPERCASE**
* 🔁 Reverse the name
* 🔢 Find the length of the name
* 😂 Generate a funny message
* 🎨 Display styled HTML output

---

## 🧠 How It Works

The app takes input from the URL using **query parameters**.

Example:

http://127.0.0.1:5000/?name=kusuma

Here:

* `name` is the parameter
* `kusuma` is the value

The Flask app processes this input and returns different outputs based on the route.

---

## ⚙️ Technologies Used

* Python
* Flask

---

## 📁 Project Structure

FlaskProject/
│
├── app.py
└── README.md

---

## 🛠️ Setup Instructions (Step-by-Step)

### 1. Clone the Repository

git clone https://github.com/your-username/your-repo-name.git

cd your-repo-name

---

### 2. Install Flask

Make sure Python is installed, then run:

pip install flask

---

### 3. Run the Application

python app.py

You will see:

Running on http://127.0.0.1:5000/

---

### 4. Open in Browser

Copy and paste the below URLs in your browser:

---

## 🌐 Available Routes

### 1️⃣ Home (Uppercase)

http://127.0.0.1:5000/?name=kusuma

👉 Output: Hello, KUSUMA!

---

### 2️⃣ Reverse Name

http://127.0.0.1:5000/reverse?name=kusuma

👉 Output: Reverse: amusuk

---

### 3️⃣ Name Length

http://127.0.0.1:5000/length?name=kusuma

👉 Output: Length: 6

---

### 4️⃣ Funny Message

http://127.0.0.1:5000/funny?name=kusuma

👉 Output: KUSUMA 😂🔥 IS AWESOME!

---

### 5️⃣ Styled Output (HTML)

http://127.0.0.1:5000/style?name=kusuma

👉 Output:

* Styled heading
* Colored text

---

## 📚 Code Explanation (Simple)

* `Flask(__name__)` → Creates the app
* `@app.route('/')` → Defines URL path
* `request.args.get('name')` → Gets user input from URL
* `upper()` → Converts to uppercase
* `[::-1]` → Reverses string
* `len()` → Finds length

---

## ⚠️ Notes

* This is a **development server**, not for production use
* Always use `debug=True` during development

---

## 💡 Future Improvements

* Add HTML forms (input box instead of URL)
* Add CSS styling for better UI
* Deploy the app online (Render / Heroku)
* Add more string operations

---

## 🙌 Author

Created by Kusuma Kumari Bodduluri

- 🔗 LinkedIn: www.linkedin.com/in/kusuma-kumari-bodduluri
- 💻 GitHub: https://github.com/kusuma990
- 🎓 Data Science Student

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it with others!

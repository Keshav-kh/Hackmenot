# 🎓 HackMeNot - An Educational Password Security Tool

## 📌 Overview

**HackMeNot** is an **interactive educational tool** designed to teach users about password security. Built with **Streamlit**, this application demonstrates how attackers crack passwords and helps users create stronger passwords while understanding the key factors affecting password security.

## 🎯 Learning Outcomes
- Understand **how passwords are evaluated** for security.
- Learn **how long it takes to crack a password** using different attack methods.
- Explore **common weaknesses** in password creation.
- Generate **stronger passwords** with minor modifications.
- Visualize **password composition and cracking time** with interactive graphs.
- Gain **practical security tips** for improving account protection.

## 🚀 Features

### 🔍 Password Analysis
- Analyzes passwords for **length, variety, and repetition**.
- Checks for **lowercase, uppercase, numbers, and special characters**.
- Penalizes passwords that contain **common patterns and repeated characters**.

### 🏆 Password Strength Score
- Assigns a **security score (0-10)** to the entered password.
- Displays **feedback messages** (Weak, Moderate, Strong, Very Strong) to educate users.

### ⏳ Estimated Cracking Time
- Uses **real-world attack speeds** to estimate how long a password would take to crack.
- Demonstrates the effectiveness of **different password strategies**.

### 🔄 Password Improvement Suggestions
- Generates **stronger variations** of the user's password.
- Uses **common security techniques** such as:
  - Character substitutions (`a → @, o → 0, s → $`)
  - Random capitalization
  - Special character inclusion

### 📊 Educational Visualizations
- **Interactive bar chart** displaying password component distribution.
- **Time-based cracking graph** to visualize password security over time.

### 🔒 Privacy-Focused UI
- **Passwords are hidden** (`••••••••`) by default.
- Users can **hover or toggle visibility** to reveal their passwords securely.

### 📖 Security Best Practices
- Includes **essential cybersecurity tips** such as:
  - Importance of **unique passwords** for different accounts.
  - How to enable **two-factor authentication (2FA)**.
  - Avoiding **phishing attacks** and recognizing scam emails.
  - Keeping **software updated** to reduce vulnerabilities.
  - Using **password managers** for better security.

---

## 🛠️ Installation & Setup

### 📥 Prerequisites
- **Python 3.7+** and **pip** installed.

### 📌 Clone the Repository
```bash
git clone https://github.com/your-repo/hackmenot.git
cd hackmenot
```

### 📌 Install Dependencies
```bash
pip install -r requirements.txt
```

### ▶️ Run the App
```bash
streamlit run app.py
```

---

## 📜 Code Structure
```
hackmenot/
│-- app.py                # Main Streamlit application
│-- requirements.txt      # Dependencies
│-- pass1.txt, pass2.txt, pass3.txt  # Common password datasets
│-- assets/               # Images, icons, and other assets
```


---

## 🌟 How to Use HackMeNot
1. **Enter a password** and view its security rating.
2. **Observe estimated cracking times** for different attack methods.
3. **Explore interactive visualizations** to understand password security.
4. **Improve your password** with AI-generated suggestions.
5. **Read best practices** and enhance your cybersecurity knowledge.

---

## 🎓 Who Should Use This Tool?
- **Students & Educators** - For teaching cybersecurity principles.
- **Individuals** - To assess and improve their personal password security.
- **Organizations** - To train employees on best password practices.

---

## 🌍 Contributing
Want to enhance **HackMeNot**? Feel free to contribute!

### 📌 To Contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Added feature X'`).
4. Push your branch (`git push origin feature-branch`).
5. Create a pull request!

---

## 📜 License
This project is **open-source** and available under the **MIT License**.

---

## 📞 Contact
- **Author**: Keshav Khandelwal
- **Email**: [keshavkh2407@gmail.com](mailto:keshavkh2407@gmail.com)
- **LinkedIn**: [keshav-kh](https://linkedin.com/in/keshav-kh)

Enjoy learning about password security! 🚀

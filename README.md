# Login & Registration System

A simple **Login and Registration System** implemented in **C, C++, and Python**.  
It demonstrates:
- User registration with **unique usernames**
- Secure password input (**masked in C**, hidden with `getpass` in Python)
- Password storage using **SHA-256 hashing**
- File-based storage (`users.txt`) for persistence

---

## 📂 Project Structure
```
login-registration-system/
│── C/login.c
│── CPP/login.cpp
│── Python/login.py
│── LICENSE
│── README.md
│── CHANGELOG.md
```

---

## 🚀 How to Run

### 🔹 C
```bash
gcc login.c -o login -lcrypto
./login
```

### 🔹 C++
```bash
g++ login.cpp -o login -lcrypto
./login
```

### 🔹 Python
```bash
python3 login.py
```

---

## 🛠 Features
- ✅ Register new users with unique usernames
- ✅ Passwords stored securely with **SHA-256 hashing**
- ✅ File-based persistence (`users.txt`)
- ✅ Password masking (hidden input)
- ✅ Works across **C, C++, and Python**

---

## 📜 License
This project is licensed under the **MIT License**.  
Developed by **Tareq Rezq**  
🔗 [LinkedIn](https://www.linkedin.com/in/tareq-rezq/)

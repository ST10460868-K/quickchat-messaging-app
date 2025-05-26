# QuickChat Messaging App

**QuickChat** is a simple, intuitive Java-based messaging application that allows users to send, discard, or store messages through a friendly graphical interface. Built with educational clarity in mind, it combines core programming principles with practical features like message hashing, JSON storage, and continuous integration.

---

## ✨ Features

* **📩 Send Messages Easily**
  Compose and send messages to international numbers. Validates inputs and ensures messages are under 250 characters.

* **🔒 Secure and Unique Messages**
  Each message is assigned a unique message ID and custom hash for authenticity and integrity.

* **📥 Store or Discard with Choice**
  Not ready to send? Choose to discard the message or store it for later use as a JSON file.

* **💻 User-Friendly GUI**
  Clean dialog-based interface using `JOptionPane` makes it easy to use, even without a terminal.

* **✅ Admin Login System**
  Basic login simulation with default credentials (`admin` / `pass123`).

* **🧪 Built-In Testing & CI**
  Comes with JUnit test coverage and GitHub Actions CI for automatic test runs on every push.

---

## 🧠 Technologies Used

* Java 17+
* Maven
* Swing (JOptionPane)
* JSON.simple
* JUnit 5
* GitHub Actions CI

---

## 🚀 Getting Started

### Run the App

```bash
mvn compile
mvn exec:java -Dexec.mainClass="com.mycompany.quickchat1.QuickChat1"
```

### Run the Tests

```bash
mvn test
```

---

## 📊 CI Badge

![Java CI](https://github.com/ST10460868-K/Quickchat-messaging-app/actions/workflows/maven-test.yml/badge.svg)

---

## 👋 Why QuickChat?

* Perfect for learning and demonstrating Java fundamentals
* Covers GUI, file handling, user input validation, and hashing
* Fully CI-integrated with GitHub Actions and unit testing
* Clean, modular structure suitable for further extension

---

## 🙌 Author

**ST10460868-K**
[GitHub Profile](https://github.com/ST10460868-K)

---

> “A message well sent is a message remembered. QuickChat makes it simple.”

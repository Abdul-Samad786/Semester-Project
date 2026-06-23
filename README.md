# Secure Cipher Messaging System (C++)

A C++ console-based application developed as part of my **Programming Fundamentals course**.

This project simulates secure communication between two users by allowing a sender to encrypt a message and a receiver to decrypt it using simple encryption techniques.

The project demonstrates fundamental programming concepts including **structures, file handling, dynamic memory allocation, encryption logic, functions, user input validation, and object interaction**.

---

## 📌 Project Objective

The objective of this project is to create a secure message communication system where:

* A sender enters personal details
* A receiver enters personal details
* A message is encrypted before transmission
* The encrypted message is stored in a file
* The receiver decrypts and reads the original message

---

# ✨ Features

✔ Sender & Receiver Information System
✔ Caesar Cipher Encryption
✔ Reverse Cipher Encryption
✔ Message Decryption
✔ File Saving & Reading
✔ Input Validation
✔ Dynamic Memory Allocation
✔ Interactive Console Interface

---

# 🛠 Technologies Used

* C++
* Object-Oriented Concepts
* File Handling
* Standard Template Library (STL)

---

# 📚 Concepts Covered

This project helped me practice:

### Programming Fundamentals

* Functions
* Structures
* Conditional Statements
* Loops
* Input Validation

### Object-Oriented Concepts

* Constructors
* Encapsulation
* Object Interaction

### Memory Management

* Dynamic Allocation (`new`)
* Memory Cleanup (`delete`)

### File Handling

* Reading Files
* Writing Files

### String Manipulation

* Encryption
* Decryption

---

# 🔐 Encryption Methods

## 1. Caesar Cipher

Each character is shifted using a user-defined key.

Example:

Original:

```
Hello World
```

Key:

```
3
```

Encrypted:

```
Khoor#Zruog
```

---

## 2. Reverse Cipher

The entire message is reversed.

Example:

Original:

```
Hello World
```

Encrypted:

```
dlroW olleH
```

---

# 📂 Project Structure

```bash
Secure-Cipher-Messaging/
│
├── main.cpp
├── encrypted_message.txt
├── README.md
```

---

# ⚙ Program Workflow

### Step 1

Enter sender information

↓

### Step 2

Enter receiver information

↓

### Step 3

Select encryption method

↓

### Step 4

Enter message

↓

### Step 5

Generate encrypted message

↓

### Step 6

Save encrypted message to file

↓

### Step 7

Receiver enters access code

↓

### Step 8

Decrypt and display original message

---

# ▶ Sample Execution

```text
Enter Sender Details

Name: Abdul Samad
ID: 36203-323233-8

Select Encryption:
1. Caesar Cipher
2. Reverse Cipher

Message:
Hello World

Key:
3

Encrypted:
Khoor#Zruog

Saved to file...

Receiver enters:
open.cipher

Decrypted:
Hello World
```

---

# 🧠 Learning Outcomes

Through this project, I learned:

* How encryption algorithms work
* Building interactive C++ applications
* File storage and retrieval
* Dynamic memory handling
* Designing modular programs

---

# 🚀 Future Improvements

* Add password protection
* Support multiple messages
* Improve encryption algorithms
* GUI implementation
* Database integration
* User authentication

---

## Author

**Abdul Samad**
Programming Fundamentals Project

```
```

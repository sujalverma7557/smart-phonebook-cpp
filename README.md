# 📞 Smart PhoneBook - C++ Contact Management System

A terminal-based Phone Book application developed in **C++** that allows users to manage contacts dynamically using a **singly linked list**. It includes features such as add, update, delete, search, validate, and sort contacts, along with input validations using **regex** for email and mobile numbers.

---

## 🚀 Features

- ✅ Add a new contact (First Name, Last Name, Phone Number, Email)
- 📋 Display all contacts in alphabetical order
- 🔍 Search contacts by name, email, or phone number
- 📝 Update contact details (name, number, email)
- ❌ Delete a single contact or all contacts
- 🔁 Merge contacts with duplicate phone numbers
- 📧 Email validation using **regex**
- 📱 Phone number validation (10-digit check)
- 🧠 Dynamic memory handling using linked list
- 🎨 Colorful UI using terminal color codes
- 💾 File structure ready for future file persistence

---

## 🛠 Tech Stack

- **Language**: C++
- **Data Structure**: Singly Linked List
- **Libraries**:
  - `<iostream>` for input/output
  - `<regex>` for email validation
  - `<algorithm>` for sorting
  - `<windows.h>` for console effects (color/sleep)

---

## 🧩 How it Works

1. On launching, it shows a loading animation and menu.
2. You can add contacts with validation for phone and email.
3. Contacts are stored in a linked list and displayed in alphabetical order.
4. Duplicate phone numbers can be merged or stored separately.
5. You can update or delete a specific contact or clear all.

---

## 📷 Sample UI

```text
--------------------------------------------
|               PHONE BOOK                 |
--------------------------------------------
|       [1]  Add a new Contact             |
|       [2]  Display All Contacts          |
|       [3]  Delete a Contact              |
|       [4]  Update a Contact              |
|       [5]  Number of Contacts            |
|       [6]  Search                        |
|       [7]  Delete All Contacts           |
|       [8]  Exit                          |
--------------------------------------------

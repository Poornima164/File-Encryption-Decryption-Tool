# 🔐 File Encryption-Decryption Tool

A simple desktop GUI application built with Python using **Tkinter** and **Cryptography** libraries. This tool allows users to securely encrypt and decrypt files using symmetric encryption (Fernet), making file handling safer and user-friendly.

---

## 🧰 Features

* 🔑 Generate encryption keys
* 📂 Select input and output files via GUI
* 🔐 Encrypt and decrypt files with a single click
* 📋 Copy key to clipboard automatically
* 📜 View and manage encryption/decryption logs
* 🧹 Clear logs with one button
* 💻 Easy-to-use graphical interface

---

## 🖥️ Technologies Used

* **Python 3**
* **Tkinter** (for GUI)
* **Cryptography** (for encryption/decryption)
* **pyperclip** (for clipboard functionality)
* **logging** (for action logging)

---

## 📦 Requirements

Install dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

> Ensure you have Python 3.9+ installed.

---

## 🚀 How to Run the Project

1. Clone the repository or download the source files.
2. Navigate to the project directory in the terminal.
3. Run the application:

```bash
python Main.py
```

---

## 🧪 How It Works

1. Launches a GUI window.
2. Select the input file to encrypt or decrypt.
3. Choose the output file name and path.
4. Generate or paste an existing Fernet key.
5. Click **Encrypt** or **Decrypt**.
6. Logs are saved to `logs.log`, viewable through the GUI.

---

## 📤 Example Output

### 🔒 Encryption And Decrytion Window
![Encryption Window](/Output.png)

---

## 📁 Logs

Logs are stored in `logs.log` and include timestamps and action details. You can view or delete them using the buttons in the GUI.

---

## 🛑 Disclaimer

* Keep your encryption key safe. Losing it will make decryption impossible.
* Do **not** share the key with unauthorized users.

---

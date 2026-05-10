# 🧰 Moduler & Packager — Multi-Utility Toolkit

A comprehensive menu-driven Python project that explores Python's powerful built-in modules — combining datetime, math, random, file handling, UUID generation and dynamic module exploration into one unified toolkit.

---

## 🚀 Features

| Module | Operations |
|---|---|
| Datetime & Time | Current date/time, date difference, custom formatting, stopwatch, countdown timer |
| Mathematics | Factorial, compound interest, trigonometry, area of geometric shapes |
| Random Data | Random number, random list element, password generator, OTP generator |
| UUID Generator | Generate unique identifiers using `uuid4()` |
| File Operations | Create, write, read, append files |
| Module Explorer | Dynamically explore attributes of any Python module |

---

## 🛠️ Tech Stack

- **Language:** Python 3.11
- **Modules Used:** `datetime`, `time`, `math`, `random`, `string`, `uuid`, `importlib`
- **Concepts:** Modular Programming, Functions, Exception Handling, `if __name__ == "__main__"`
- **Tool:** Jupyter Notebook

---

## 📁 Project Structure

```
python-modules-packages/
│
├── Moduler_packager.ipynb   # Main Jupyter Notebook
└── README.md                # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository
```bash
git clone https://github.com/ravindra-data/python-modules-packages.git
```

2. Open the notebook
```bash
jupyter notebook Moduler_packager.ipynb
```

3. Run the cell and explore the toolkit from the main menu!

---

## 📸 Sample Output

```
___________________________________________________
        Welcome to Multi-Utility Toolkit
___________________________________________________

=== Main Menu ===
1. Datetime and Time Operations
2. Mathematical Operations
3. Random Data Generation
4. Generate Unique Identifier
5. File Operations
6. Explore Module Attributes
7. Exit

--- Sample Outputs ---
Current Date and Time : 2026-05-10 19:30:00
Factorial of 7        : 5040
Compound Interest     : ₹1628.89 on ₹10000 @ 5% for 3 years
Random Password       : xK#9mP!2qL
Your OTP              : 847321
UUID                  : 3f7c2e1a-9b4d-4f0e-8a1c-2d5e6f7g8h9i
```

---

## 💡 What I Learned

- Importing and using multiple Python standard library modules
- Building a multi-level nested menu system
- Implementing robust exception handling with `try/except`
- Generating secure random passwords and OTPs using `string` + `random`
- Dynamically inspecting module attributes using `importlib`
- Using `if __name__ == "__main__"` for proper script execution

---

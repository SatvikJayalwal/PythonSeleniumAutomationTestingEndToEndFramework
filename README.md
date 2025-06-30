# PythonSeleniumEndToEndFramework
# 🧪 Selenium PyTest Automation Framework

This is a modular, data-driven automation testing framework built using **Python**, **Selenium**, and **PyTest**, designed for end-to-end testing of web applications. It follows the **Page Object Model (POM)** design pattern and supports HTML reporting, cross-browser execution, and automatic screenshots on test failure.

---

## 🚀 Features

- ✅ Page Object Model (POM) structure
- 📂 JSON-based test data input
- 📷 Auto screenshot on test failure
- 📊 HTML reports using `pytest-html`
- 🌐 Cross-browser testing (Chrome & Edge)
- 🧪 PyTest fixtures and hooks for clean setup/teardown
- 🪝 Jenkins-compatible for CI/CD execution

---

## 🗂️ Project Structure


e2e_TestFramework/
│
├── data/
│ └── test_e2e_TestFramework.json # Test input data
│
├── pages/
│ ├── login.py # LoginPage class (POM)
│ ├── ShopPage.py # ShopPage class (POM)
│ └── checkout_confirmation.py # Checkout page logic
│
├── utils/
│ └── browserutils.py # Base utilities (getTitle, etc.)
│
├── test_e2e_TestFramework.py # Main test file
├── conftest.py # PyTest fixture, hooks, CLI args
├── report.html # Generated test report
├── screenshots/ # Auto-saved failure screenshots
└── requirements.txt # Dependencies

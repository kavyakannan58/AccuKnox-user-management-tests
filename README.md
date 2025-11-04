** AccuKnox QA Trainee Practical Assessment – User Management Automation**

This project is developed as part of the AccuKnox QA Trainee Practical Assessment.
It automates the User Management module of the OrangeHRM demo web application using Playwright (Python + Pytest).

🎯 Objective

To automate the end-to-end User Management flow in OrangeHRM, covering the following actions:

Login to the OrangeHRM portal

Navigate to the Admin module

Add a new user

Search and validate the created user

Edit and verify updated user details

Delete the user from the system


**AccuKnox-user-management-tests/**
│
├── pages/                # Page Object Model classes
│   ├── login_page.py
│   └── admin_page.py
│
├── tests/                # Pytest test scripts
│   ├── test_add_user.py
│   ├── test_search_user.py
│   ├── test_edit_user.py
│   ├── test_validate_user.py
│   └── test_delete_user.py
│
├── conftest.py           # Browser fixture setup
├── requirements.txt      # Dependencies
├── README.md             # Project documentation
└── AccuKnox_User_Management_TestCases.xlsx  # Manual test cases




**Setup Instructions**
1️⃣ Prerequisites
Python 3.8 or above
Node.js (optional, for Playwright dependencies)
Git installed on your system

**2️⃣ Install Dependencies**
pip install -r requirements.txt
playwright install

**▶️ Running the Tests**

**Run all test cases:**
pytest --headed -q


**Run specific test file:**
pytest tests/test_add_user.py --headed

**Run in headless mode (without opening browser):
**
pytest --headless

🧪 Playwright Version Used

Playwright v1.48.0
Pytest v8.3.3

**📊 Manual Test Cases**

All manual test scenarios are documented in the Excel file:
AccuKnox_User_Management_TestCases.xlsx
**It includes:**

Test Scenario
Pre-conditions
Steps
Test Data
Expected Result

**🧠 Notes**

Project follows Page Object Model (POM) for scalability and reusability.
Uses meaningful selectors and explicit waits for stability.
Designed to demonstrate both manual and automation QA skills. 

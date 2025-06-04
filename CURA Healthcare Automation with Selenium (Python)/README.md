# CURA Healthcare Automation with Selenium (Python)

This project automates the complete workflow of the **CURA Healthcare Service** demo site using **Selenium WebDriver**, following industry-standard practices like **OOP structure**, **modular code**, **logging**, **screenshots**, **CSV export**, and **Pytest-based testing**.

## 🚀 Features

- ✅ Automated login with username/password
- ✅ Dropdown, radio button, and checkbox interaction
- ✅ Calendar date selection using dynamic XPath
- ✅ Appointment submission and validation
- ✅ Screenshot capture of appointment confirmation
- ✅ Export appointment details to CSV
- ✅ Robust logging system
- ✅ Automated tests with Pytest

---

## 🖼️ Demo Site

- URL: [CURA Healthcare Service](https://katalon-demo-cura.herokuapp.com/)

---

## 📁 Project Structure

ura_automation_project/
│
├── main.py # Orchestrates the automation flow
├── base_page.py # Reusable methods for browser interaction
├── make_appointment.py # Appointment-specific logic
├── requirements.txt # Project dependencies
├── README.md # Project info
│
├── tests/
│ └── test_main.py # Pytest test cases
│
└── screenshots/ # Saved screenshots (created automatically)


---

## 📦 Requirements

- Python 3.7+
- Google Chrome
- ChromeDriver (compatible version)

Install dependencies:
```bash
pip install -r requirements.txt

▶️ How to Run
Run the automation script:
python main.py

Run the tests:
pytest tests/test_main.py

📸 Output
Screenshot saved in the screenshots/ folder

Appointment data saved to appointment.csv

Logs saved to logfile.log

🔧 Tools Used
Selenium WebDriver

Python Standard Libraries: csv, logging, datetime

Pytest for testing

XPath for precise element targeting


📚 Real-World Use Cases
Automating appointment booking systems

Testing healthcare or scheduling platforms

Demonstrating QA Automation skills with Python + Selenium

📄 License
This project is for educational purposes only.

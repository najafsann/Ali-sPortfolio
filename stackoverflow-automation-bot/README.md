# 💻 Stack Overflow Automation Bot (POM-Based)

This project is an automated scraper built with **Selenium**, using a **Page Object Model (POM)** architecture. It logs into Stack Overflow and extracts answer data from a selected question post.

---

## 🚀 Features

- Modular, maintainable POM-based structure
- Extracts answer text from selected questions
- Screenshot capture before and after scraping
- Manual login support (CAPTCHA bypass)
- Reusable and clean scraping logic

---

## 📂 Project Structure

- `base_page.py` — Reusable utility methods for element handling
- `login_page.py` — Handles the login process
- `homepage.py` — Extracts answers from a Stack Overflow post
- `main.py` — Orchestrates the automation process

---

## ⚙️ Requirements

Install the required Python libraries with:

```bash
pip install -r requirements.txt

▶️ How to Run
Clone this repository:
git clone https://github.com/your-username/stackoverflow-automation-bot.git
cd stackoverflow-automation-bot

Install dependencies:
pip install -r requirements.txt

Run the script:
python main.py

Manually complete the login process (including CAPTCHA), then continue.

🧠 Skills Demonstrated
Selenium Automation

Page Object Model (POM) Design Pattern

WebDriverWait for dynamic content handling

Scroll & click simulation

Screenshot capture for debugging and verification

⚠️ Disclaimer
Educational Use Only — This tool is intended strictly for learning purposes. Scraping websites like Stack Overflow may violate their Terms of Service. Always ensure you have permission before using automation tools on any platform.


# 🛍️ Daraz Product Automation Scraper (POM-Based)

This is a Selenium-based scraper that automatically searches **Daraz** through Bing, navigates to product listings, and extracts product details like title and price. The code follows a clean **Page Object Model (POM)** structure.

---

## 🚀 Features

- Searches Daraz via Bing
- Navigates to the site and scrapes product listings
- Extracts:
  - Product Title
  - Product Price
- Saves results to a JSON file
- Structured using POM for clean, reusable code

---

## 📂 Project Structure

- `base_page.py` — Common reusable wait/send methods
- `home_page.py` — Searches for Daraz on Bing and opens site
- `search_results_page.py` — Sends product search query
- `product_page.py` — Extracts product data
- `main.py` — Orchestrates the automation flow

---

## ⚙️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt

▶️ How to Run:
python main.py
The bot will:

Open Bing

Search for "Daraz"

Click Daraz link

Search for "smartphones"

Scrape titles & prices

Save data to DarazProducts JSON file

🧠 Skills Demonstrated
Selenium Web Automation

POM (Page Object Model)

Dynamic waits & DOM targeting

JSON data structuring

⚠️ Disclaimer
For educational use only.
Respect website terms of service. Avoid spamming or overloading websites with scrapers.

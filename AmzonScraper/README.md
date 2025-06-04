# 🛒 Amazon Price Scraper with Selenium

This project is a web automation and data scraping tool that uses **Selenium** to extract product information from Amazon based on a search query.

---

## 🔍 Features

- Extracts:
  - Product Title
  - Price
  - Rating
  - Image URL
  - Product URL
- Handles multi-page navigation
- Includes anti-bot techniques to avoid detection
- Saves data into a `JSON` file
- Clean and readable code structure

---

## 📁 Output Sample

Data is saved as a list of products in JSON format:

```json
[
  {
    "Title": "Example Product",
    "Price": 299.99,
    "Rating": "4.5 out of 5",
    "Image": "https://example.com/image.jpg",
    "Url": "https://amazon.com/product-link"
  }
]


🔧 Requirements
Install the required Python libraries using:
pip install -r requirements.txt

▶️ How to Run
Clone the repo

Install requirements

Run the script:
python main.py


🧠 Skills Demonstrated
Selenium WebDriver & DOM handling

Automation evasion techniques

Dynamic waiting with WebDriverWait

Clean data structuring and JSON output

📌 Note
This scraper is for educational purposes only.
Always follow Amazon’s Terms of Service.

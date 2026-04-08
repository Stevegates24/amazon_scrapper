# 📦 Amazon Product Scraper

Extract ASIN, Price and Brand from any Amazon product page in one click — paste directly into Excel without overwriting your existing data.

---

## ✨ Features

* 🔑 Extract ASIN (10-digit product ID)
* 💰 Extract Price (any currency, number only)
* 🏷️ Extract Brand (or "Brand NA" if not listed)
* 🌍 Works on 16 Amazon domains worldwide
* 🌙 Dark mode with persistent preference
* 🛡️ Zero data collected — runs 100% locally

---

## 🌐 Supported Domains

`amazon.com` · `amazon.in` · `amazon.co.uk` · `amazon.de` · `amazon.ca` · `amazon.com.au` · `amazon.co.jp` · `amazon.fr` · `amazon.es` · `amazon.it` · `amazon.nl` · `amazon.se` · `amazon.pl` · `amazon.ae` · `amazon.sa` · `amazon.sg`

---

## 📥 Installation (under 60 seconds)

Open the [Amazon Scraper Extension Page](https://stevegates24.github.io/amazon_scrapper/)

### Chrome

1. [Download ZIP](https://github.com/Stevegates24/amazon_scrapper/archive/refs/heads/main.zip)
2. Extract it
3. Open `chrome://extensions/`
4. Enable **Developer Mode** (top-right toggle)
5. Click **Load Unpacked**
6. Select the `amazon_scrapper-main` folder

### Firefox

Available on [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/amazon-product-scraper/) — or search **Amazon Product Scraper** by Steve Gates.

---

## ⚡ Usage

1. Open any Amazon product page
2. Click the extension icon in your toolbar
3. Click **🔍 Scrape Page**
4. Use the two copy buttons:
   - **📋 ASIN + Price** → click your ASIN cell in Excel → `Ctrl+V`
   - **🏷️ Brand** → click your Brand cell in Excel → `Ctrl+V`

> Two targeted pastes. Nothing else in your spreadsheet gets overwritten.

---

## 📊 Excel Column Map

| Col | Header | Source |
|-----|--------|--------|
| A | Mapped ASIN | ✅ auto — ASIN+Price button |
| B | Amazon Price | ✅ auto — ASIN+Price button |
| C | Temu Price | ✍️ you fill |
| D | Inexact Reason Code | ✍️ you fill |
| E | Temu Brand | ✍️ you fill |
| F | Amazon Brand | ✅ auto — Brand button |

---

## 🔒 Privacy

This extension does not collect, transmit or store any data.  
Everything runs locally in your browser. No servers. No tracking. No accounts.

---

## 🧠 Notes

- Wait for the Amazon page to **fully load** before clicking Scrape.
- If scraping fails, refresh the page and try again.
- The ASIN is also extracted from the URL as a fallback if it's not in the product details table.
- Price is extracted as a plain number — currency symbols are stripped automatically.

---

## 👤 Author

Built by **Steve Gates** · v1.0.0  
Not affiliated with Amazon.com, Inc.

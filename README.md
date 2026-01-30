# 📱 SmartPhone Price Tracker (PriceOye.pk Automation)

A high-performance Python automation tool designed to monitor mobile phone prices from **PriceOye.pk**. It scrapes real-time data, maintains a historical Excel database, and alerts you whenever a price drop or hike is detected.

---

## 🚀 Key Features
- **Live Web Scraping:** Uses `BeautifulSoup4` to extract retail and discounted prices directly from product pages.
- **Automated Excel Database:** Automatically creates and updates `SmartPhone Price Tracker.xlsx` using `openpyxl`.
- **Intelligent Price Alerts:**
  - 📉 **Drop Alert:** Notifies you if the price decreases from the last check.
  - 📈 **Hike Alert:** Notifies you if the price has increased.
- **Persistent Logging:** Keeps a date-wise history of price trends for market analysis.
- **Zero Manual Entry:** Streamlines the data collection process, saving hours of manual work.

---

## 🛠️ Technical Stack
- **Language:** Python 3.x
- **Libraries:** `Requests`, `BeautifulSoup4`, `Openpyxl`
- **Automation:** Logic-based price comparison and file handling.

---

## ⚙️ Installation & Usage

### 1. Clone this repository
git clone https://github.com/mu-abdullahdev/smartphone-price-tracker.git
cd smartphone-price-tracker

### 2. Install required libraries
pip install requests beautifulsoup4 openpyxl

### 3. Run the script
python main.py

---

## 📊 Sample Data Preview
The script generates/updates an Excel report with the following structure:

| SmartPhone Name | Retail Price | Sale Price | Date |
| :--- | :--- | :--- | :--- |
| Samsung Galaxy A07 | 45000 | 42999 | 2026-01-30 |
| Honor X7c | 55000 | 54500 | 2026-01-30 |

> **Terminal Output Example:**
> `Alert! Samsung Galaxy A07 price dropped by 2001 Rs!`

---

## 👨‍💻 Developer Information
**Muhammad Abdullah**
Computer Science Student at **Emerson University Multan**
- **LinkedIn:** [in/muhammad-abdullah-12a58038a](https://linkedin.com/in/muhammad-abdullah-12a58038a)
- **GitHub:** [@mu-abdullahdev](https://github.com/mu-abdullahdev)
- **Email:** muabdullah0809@gmail.com

---
*Disclaimer: This project is for educational purposes only. Please use it responsibly and respect the target website's Terms of Service.*

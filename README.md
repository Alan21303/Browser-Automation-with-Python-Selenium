# 🌐 Browser Automation with Python & Selenium

This project demonstrates **web browser automation** using **Python + Selenium**.  
It includes examples of **form filling, button clicks, and data-driven testing** using an Excel file.

---

## 📌 Features

- ✅ Automates repetitive browser tasks
- ✅ Data-driven testing using Excel (`userdata.xlsx`)
- ✅ Demonstrates form submissions & button clicks
- ✅ Easily customizable for different use cases
- ✅ Beginner-friendly project structure

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:** Selenium, openpyxl (for Excel handling)
- **Browser:** Chrome (via ChromeDriver)

---

## 📂 Project Structure

browser-automation/
│── create_users.py # Reads user data from Excel & automates signup
│── web_automation.py # Core automation script
│── userdata.xlsx # Test data (username/password list)
│── README.md # Documentation

yaml
Copy code

---

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Alan21303/Browser-Automation-with-Python-Selenium.git
   cd Browser-Automation-with-Python-Selenium
   Create and activate a virtual environment
   ```

bash
Copy code
python -m venv venv
source venv/bin/activate # Linux/Mac
venv\Scripts\activate # Windows
Install dependencies

bash
Copy code
pip install selenium openpyxl
Download ChromeDriver

Check your Chrome version → Download ChromeDriver

Place it in your project folder or add to system PATH.

🚀 Running the Scripts
Run form automation

bash
Copy code
python web_automation.py
Run data-driven user creation (reads from userdata.xlsx)

bash
Copy code
python create_users.py
📸 Example
Automating form submission with multiple users from Excel:

Username Password
user1 pass1
user2 pass2

🚧 Future Enhancements
Add support for multiple browsers (Firefox, Edge).

Store results (pass/fail) back into Excel.

Integrate reporting with pytest + HTML reports.

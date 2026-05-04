# IT23347762 – IT3040 Assignment 1

## 📌 Project Title
Automated Testing for Singlish to Sinhala Transliteration System

---

## 📂 Repository
https://github.com/IBL11/IT23347762_IT3040_Assignment1_singlish-sinhala-automation.git

---

## 🧩 Project Overview
This project implements an automated testing framework for a Singlish to Sinhala transliteration web application using **Playwright automation testing**.

The system reads structured test cases from an Excel file, performs automated UI interactions on the web application, and validates the generated Sinhala output against expected behavior. The final results are automatically recorded back into the Excel sheet with a PASS/FAIL status.

This approach reduces manual testing effort and ensures consistent validation across multiple input scenarios, especially for complex multilingual inputs.

---

## 🎯 Objectives
- Automate UI testing for a Singlish to Sinhala transliteration system  
- Execute test cases using Excel-based data-driven testing  
- Validate transliteration output automatically  
- Record test results (PASS/FAIL) into Excel  
- Improve testing efficiency and repeatability  

---

## 📁 Project Structure

IT3040_Assignment_1/

- IT23347762_test_automation.py → Playwright automation script  
- IT23347762_Assignment 1_Test cases.xlsx → Excel file containing test cases & results  
- requirements.txt → Python dependencies  
- IT23347762_README.md → Project documentation  
- venv/ (optional) → Virtual environment (not required for submission)

---

## ⚙️ Technologies Used

- Python (Core scripting language)  
- Playwright (Browser automation framework)  
- OpenPyXL (Excel file handling and updates)  

---

## 🚀 How to Run the Project

### Step 1: Open terminal in project folder
cd IT23347762  

### Step 2: (Optional) Activate virtual environment
venv\Scripts\activate  

### Step 3: Install dependencies
pip install -r requirements.txt  
playwright install  

### Step 4: Run automation script
python IT23347762_test_automation.py --excel "IT23347762/IT23347762_Assignment 1_Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 -
slow-mo-ms 200 --save-every 1 --keep-open

---

## 📊 Output Description

- The system captures actual transliteration output from the web application  
- Results are automatically updated in the Excel file  
- Each test case is marked as:
  - **PASS** → Output matches expected behavior  
  - **FAIL** → Output mismatch detected  

Additional columns updated:
- Actual Output  
- Status (PASS/FAIL)  

---

## 🧪 Test Case Details

- **Total Test Cases:** 50+  
- **Testing Type:** Negative + Edge Case Testing  

### Covered Scenarios:
- Mixed language inputs (Singlish + English)  
- Spelling variations and phonetic differences  
- Emojis and special symbols  
- Real-world scenarios (banking, travel, messaging apps)  
- System-related inputs (errors, logs, commands)  
- Numeric, date, and structured inputs  
- Unexpected and edge-case user behavior  

---

## ⚠️ Important Notes

- The system uses strict string comparison for validation  
- Minor differences in spacing, punctuation, or transliteration style may result in FAIL  
- Some failures are expected due to:
  - Natural ambiguity in Singlish transliteration  
  - Inconsistent phonetic mapping  
  - UI response timing delays  

---

## 🎓 Student Information

- **Student ID:** IT23347762  
- **Module:** IT3040  
- **Assignment:** Assignment 1 (Option 1)  
- **Implementation Type:** Automated UI Testing Project  

---

## 📌 Key Highlights

✔ Data-driven testing using Excel  
✔ Fully automated browser interaction  
✔ Real-time result validation  
✔ Covers edge cases and negative scenarios  
✔ Reduces manual testing effort significantly  

---

## ✅ Final Status

✔ Automation script successfully implemented  
✔ Excel-based validation working correctly  
✔ Multiple test scenarios executed  
✔ End-to-end testing completed  

---

## 📌 Submission Notes

- Virtual environment (venv) is excluded from submission  
- All required files are included  
- Project runs directly using requirements.txt  
- No manual intervention required after execution  
# IT3040 Assignment 1 – QA Automation

https://github.com/GeethmiUduwana/IT23653740_ITPM_assignment01_option01.git

## Project Title

Automated Testing for Singlish to Sinhala Transliteration System

---
## Student Information

* Name: UDUWANA G.S
* Student ID: IT23653740
* Module: IT3040
* Assignment: Assignment 1 (Option 1)

---

## Project Structure

```
IT23653740/
│
├── IT23653740_test_automation.py
├── IT23653740_Assignment 1 - Test cases.xlsx
├── IT23653740_requirements.txt
├── IT23653740_README.md
```

---

## Setup & Run Commands

```bash
py -m pip install -U pip
py -m pip install playwright openpyxl
py -m playwright install

py IT23653740_test_automation.py --excel "IT23653740_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

---

## Technologies Used

* Python
* Playwright (UI Automation)
* OpenPyXL (Excel Handling)

---

## Output

* Results are automatically written to the Excel file
* Updated columns:

  * Actual Output
  * Status (PASS / FAIL)

---

## Test Case Details

* Total Test Cases: 60
* Test Type: Negative Testing

### Covered Scenarios:

* Mixed language inputs (Singlish + English)
* Spelling variations
* Emojis & symbols
* Real-world conversational inputs
* System-like messages
* Numeric and date inputs

---

## Important Notes

* The system uses strict comparison
* Even small differences (spacing, punctuation, spelling) may result in FAIL
* Some failures are expected due to:

  * Transliteration inconsistencies
  * Mixed language complexity
  * UI/API instability

---



## Final Status

 Automation script successfully implemented
 Excel-based validation completed
 Wide test coverage with edge cases
 

---

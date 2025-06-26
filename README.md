# Cermati Registration Automation

This repository contains a Selenium-based automation script for testing the registration process on [Cermati.com](https://www.cermati.com/gabung). It covers the positive test scenario, filling in all required fields with valid data and submitting the form successfully.

---

## Tools & Frameworks Used

- Language: Python 3.x
- Framework: Selenium WebDriver
- Browser Driver: ChromeDriver
- Testing Approach: Manual wait and dynamic element handling with WebDriverWait

---

## Test Scenario

Positive Case - Register a New User

Steps automated:
1. Navigate to: https://www.cermati.com/gabung
2. Fill in the following required fields:
   - Email
   - Mobile Phone
   - Full Name
   - Password & Confirm Password
   - City (Dropdown selection)
3. Accept Terms & Conditions
4. Submit the registration form

---

## Project File

- `cermati_register_test.py` — The main automation script

---

## How to Run the Script

1. Install Python packages

Make sure you have Python installed, then run:
```
pip install selenium
```

2. Download ChromeDriver

Ensure [ChromeDriver](https://sites.google.com/chromium.org/driver/) is installed and matches your Chrome version.
- Add it to your system PATH or specify its location in the script.

3. Run the script
```
python cermati_register_test.py
```

This will:
- Launch Chrome
- Fill the form with valid test data
- Click submit
- Close the browser after a short delay

---

## Notes

- This test only covers positive cases (valid inputs).
- You can extend it to include negative tests, form validations, and screenshot capturing.
- Email/phone used are dummy data — no real registration is completed.

---

## Author

Dandy E. Purwanto  
Manual QA Engineer | Passionate in Automation Testing  
GitHub: [https://github.com/dandypurwanto](https://github.com/dandypurwanto)

---

## Contact

Feel free to fork this repo, open an issue, or reach out if you'd like to collaborate or provide feedback.

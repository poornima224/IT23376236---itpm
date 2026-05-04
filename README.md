# IT23376236---itpm

🚀 Playwright Test Automation for Chat Translator
This project is a robust automation suite designed to validate the Singlish-to-English Chat Translator on the Pixels Suite platform. It utilizes Python and Playwright to execute a comprehensive set of 50 test cases, ensuring high translation accuracy and system reliability.

📋 Project Overview
The primary goal of this project is to automate the testing of linguistic translations. It reads test data from an Excel spreadsheet, performs real-time translations via a web interface, and logs the actual results back into the spreadsheet for final evaluation.

Target URL: Pixels Suite Chat Translator

Test Scope: 50 unique Singlish input variations including questions, slang, and mixed-mode sentences.

✨ Features
Data-Driven Testing: Fully integrated with Microsoft Excel for test case management.

Dynamic Waiting: Configurable timeouts to handle varying network speeds.

Detailed Logging: Captures "Actual Output" and "Pass/Fail" status automatically.

Browser Flexibility: Supports Chromium, Firefox, and WebKit through Playwright.

🛠️ Tech Stack
Language: Python 3.x

Automation Framework: Playwright

Data Handling: Pandas & Openpyxl

Tools: VS Code, Git/GitHub

🚀 Getting Started
1. Prerequisites
Ensure you have Python installed on your system. You will also need to install the following dependencies:

Bash
# Install Playwright and required libraries
pip install playwright pandas openpyxl

# Install browser binaries
python -m playwright install
2. File Setup
Ensure your project folder is structured as follows:

test_automation.py (The main script)

Assignment 1 - Test cases.xlsx (The test data file)

3. Running the Automation
Execute the following command in your terminal to start the test suite:

PowerShell
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 7000 --type-delay-ms 100 --save-every 1 --keep-open
📊 Test Categories Covered
The test suite validates various Singlish linguistic patterns, including:

Basic Greeting forms

Question-based structures

Mixed Singlish/English (Code-switching)

Sentences with Special Characters & Emojis

Numerical and Date formats

👤 Author
Poornima Wijayabandara

Third-year IT Undergraduate

Sri Lankan Institute of Information Technology (SLIIT)

Pro-Tips for Your Submission:
Screenshot: Add a folder named screenshots to your repo and include a picture of your terminal running the code.

License: Adding a simple MIT License file makes your repository look even more professional.

Repo Name: Name your repository something clear, like Singlish-Translator-Automation.

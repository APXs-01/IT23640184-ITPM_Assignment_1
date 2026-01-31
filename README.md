# IT23640184-ITPM_Assignment_1

## Project Overview
This repository contains the automated test suite for the **SwiftTranslator (Singlish to Sinhala)** web application. The suite includes:
* **24 Positive test scenarios**
* **10 Negative test scenarios**
* **UI-related test cases** Developed as part of the requirements for **IT3040-ITPM Assignment 1**.

---

## Prerequisites
Before running the tests, ensure you have the following installed:
* **Node.js** (v16 or higher recommended)
* **npm** (included with Node.js)

---

## Git Repository Link
[https://github.com/APXs-01/IT23640184-ITPM_Assignment_1.git](https://github.com/APXs-01/IT23640184-ITPM_Assignment_1.git)

---

## Installation & Setup Instructions

### 1. Clone the Repository
```bash
git clone [https://github.com/APXs-01/IT23640184-ITPM_Assignment_1.git](https://github.com/APXs-01/IT23640184-ITPM_Assignment_1.git)
cd IT3040_Assignment1_IT23640184

2. Install Dependencies
Bash
npm install
npx playwright install
3. Run All Tests
To run the tests in headed mode (where you can see the browser open):

Bash
npx playwright test --headed
Note: To run in headless mode (faster, background execution), simply use: npx playwright test

4. View the Test Report
After the tests complete, generate and view the HTML report:

Bash
npx playwright show-report
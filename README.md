# Playwright POM Automation Framework

This project demonstrates UI test automation using **Playwright with TypeScript** following the **Page Object Model (POM)** design pattern.

## 🔧 Tech Stack
- Playwright
- TypeScript
- Node.js

## 📁 Project Structure
src/pages → Page Object classes
tests/login → Test cases (positive & negative scenarios)
playwright.config.ts → Playwright configuration


## ✅ Test Scenarios Covered
- Valid login flow
- Invalid login flow with error validation

## ▶️ How to Run Tests
1. Install dependencies:
   ```bash
   npm install
2. Run all tests:
    npx playwright test --headed

Tests are written against:
https://www.saucedemo.com/


👉 Save the file.

---

## 🧠 INTERVIEW PREP – HOW TO EXPLAIN THIS PROJECT

Memorize this **simple explanation** (no jargon overload):

> “I built a Playwright automation framework using TypeScript and Page Object Model.  
> I automated positive and negative login scenarios on SauceDemo, keeping UI locators and actions inside page classes and validations inside tests.  
> The framework is clean, reusable, and easy to extend.”

This answer alone puts you ahead of many candidates.

---

## 🧩 STEP 8.3 – Push to GitHub (When You’re Ready)

### Recommended repo name:

### Basic commands (no rush):
```bash
git init
git add .
git commit -m "Initial Playwright POM framework with login tests"
git branch -M main
git remote add origin <your-github-repo-url>
git push -u origin main



# selenium-With-Java-login-automation
"Automated login test using Selenium WebDriver in Java"

# 🔐 Selenium Login Automation (Java + WebDriver)

This project demonstrates automated login testing using **Selenium WebDriver** in Java. It automates a real-world scenario of logging into a test website and validating both successful and unsuccessful login attempts.

---

## 🛠️ Tech Stack

- Java
- Selenium WebDriver
- ChromeDriver
- Git & GitHub

---

## 🌐 Test Website

Practice site used for automation:  
🔗 [https://practicetestautomation.com/practice-test-login/](https://practicetestautomation.com/practice-test-login/)

---

## ✅ Features

- Launch browser using ChromeDriver
- Enter valid credentials and login
- Verify success message or redirection
- Test with invalid password and capture error
- Demonstrates usage of different Selenium **locators**:
  - `By.id()`
  - `By.name()`
  - `By.className()`
  - `By.tagName()`
  - `By.linkText()`
  - `By.partialLinkText()`
  - `By.cssSelector()`
  - `By.xpath()`

---

## 🔁 Test Scenarios

### ✅ Valid Login Test
- **Username**: `student`
- **Password**: `Password123`
- ✅ Expected: Success message or dashboard

### ❌ Invalid Login Test
- **Username**: `student`
- **Password**: `WrongPassword`
- ❌ Expected: Error message like “Your password is invalid!”

---

## 📁 Project Structure



# Sauce Demo Test Cases

Comprehensive test case documentation for the Sauce Demo e-commerce application. This repository contains detailed test cases covering login, product browsing, shopping cart, and checkout functionality.

## 📋 Overview

This project provides a complete set of test cases for the Sauce Demo application (https://www.saucedemo.com/), a practice application designed for testing automation frameworks like Playwright, Selenium, and Cypress.

**Total Test Cases:** 37
**Modules:** 4  
**Status:** Passed, Failed & Skipped

## 📊 Test Coverage

### 1. Login Tests (8 test cases)
- Valid login with standard user credentials
- Locked out user handling
- Invalid credentials validation
- Empty field validation (username & password)
- Special user types (problem user, performance glitch user)
- Logout functionality

**Priority:** High  
**Status:** Passed

### 2. Product Tests (11 test cases)
- View product list and details
- Add/remove products from cart
- Product sorting (by name A-Z, Z-A, price low-high, high-low)
- Product image and price display
- Product description visibility

**Priority:** High/Medium  
**Status:** Passed/Skipped

### 3. Cart Tests (9 test cases)
- View empty and populated cart
- Update item quantities
- Remove items from cart
- Cart total calculation
- Continue shopping functionality
- Proceed to checkout
- Cart badge count verification
- Cart persistence after page refresh

**Priority:** High/Medium  
**Status:** Passed

### 4. Checkout Tests (9 test cases)
- Checkout page display
- Shipping information entry
- Form validation (first name, last name, postal code)
- Order summary review
- Complete purchase flow
- Order confirmation
- Navigation back to products

**Priority:** High/Medium  
**Status:** Passed

## 📁 File Structure

```
Sauce_Demo_Test_Cases/
├── README.md                                    # This file
├── Sauce_Demo_Test_Cases_YYYYMMDD_HHMMSS.xlsx  # Generated test cases Excel file
└── generate_test_cases.py                       # Python script to generate Excel file
```

## 📄 Test Case Format

Each test case includes:
- **Test ID:** Unique identifier (e.g., TC_LOGIN_001)
- **Test Name:** Descriptive name of the test
- **Description:** Detailed explanation of what is being tested
- **Precondition:** Required state before executing the test
- **Test Steps:** Step-by-step instructions to execute the test
- **Expected Result:** What should happen after executing the steps
- **Priority:** High, Medium, or Low
- **Status:** Passed, Failed & Skipped

## 🔐 Test User Credentials

The Sauce Demo application provides special test users for different scenarios:

| Username | Password | Behavior |
|----------|----------|----------|
| `standard_user` | `secret_sauce` | Normal user experience |
| `locked_out_user` | `secret_sauce` | Account locked error |
| `problem_user` | `secret_sauce` | UI glitches and issues |
| `performance_glitch_user` | `secret_sauce` | Slow loading times |

## 📊 Excel File Features

The generated Excel file includes:

- **Summary Sheet:** Overview of test statistics by module
- **Login Tests Sheet:** All login-related test cases
- **Product Tests Sheet:** Product browsing and interaction tests
- **Cart Tests Sheet:** Shopping cart functionality tests
- **Checkout Tests Sheet:** Checkout and purchase flow tests

### Formatting
- Color-coded status (Green = Passed, Yellow = Skipped, Red = failed)
- Frozen header rows for easy scrolling
- Optimized column widths for readability
- Professional styling with borders and fills

## 📈 Test Statistics

| Module | Total | Active | Skipped |
|--------|-------|--------|---------|
| Login | 8 | 8 | 0 |
| Product | 11 | 9 | 2 |
| Cart | 9 | 9 | 0 |
| Checkout | 9 | 9 | 0 |
| **TOTAL** | **37** | **35** | **2** |


## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Created for QA testing and automation practice.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new test cases
- Improve existing test cases

---

**Last Updated:** January 7, 2026  
**Version:** 1.0.0

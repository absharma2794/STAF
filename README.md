# STAF — Selenium Test Automation Framework

UI test automation framework for [SauceDemo](https://www.saucedemo.com), a demo e-commerce site. Built with Java, Selenium WebDriver, TestNG and Maven, using the Page Object Model.

> **Status:** in progress (started Nov 2026).

## Tech stack

| Area | Tool |
|---|---|
| Language | Java |
| Browser automation | Selenium WebDriver |
| Test runner | TestNG |
| Build | Maven |
| Design pattern | Page Object Model |

## Coverage

- [ ] Login: valid user, locked-out user, invalid credentials
- [ ] Inventory: product list, sorting
- [ ] Cart: add and remove items
- [ ] Checkout: customer details, order overview, order complete

## Getting started

Prerequisites:

- JDK 11 or newer
- Maven 3
- Google Chrome (Selenium Manager downloads the matching driver automatically)

Run the tests:

```bash
git clone https://github.com/absharma2794/STAF.git
cd STAF
mvn test
```

## Test data

SauceDemo lists its demo accounts on its login page. They all use the password `secret_sauce`:

- `standard_user`
- `locked_out_user`
- `problem_user`
- `performance_glitch_user`

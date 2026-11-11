# QA Automation Framework with Playwright

An end-to-end (E2E) automated testing suite built with **Playwright** and **JavaScript** to validate web application functionality, page navigation, and user interactions.

---

## 🛠️ Tech Stack & Tools

* **Testing Framework:** [Playwright](https://playwright.dev/)
* **Language:** JavaScript / Node.js
* **Version Control:** Git & GitHub
* **CI/CD Integration:** GitHub Actions

---

## 📁 Repository Structure

```text
qa-automation/
├── .github/
│   └── workflows/
│       └── playwright.yml    # GitHub Actions CI/CD configuration
├── tests/
│   └── example.spec.js      # Sample Playwright test scripts
├── .gitignore               # Ignored files (node_modules, test-results, etc.)
├── package.json             # Project dependencies and script shortcuts
├── package-lock.json        # Dependency lockfile
└── playwright.config.js     # Global Playwright configuration file
```

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Node.js installed on your machine.
* [Download Node.js](https://nodejs.org/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/madalasumanth2001/qa-automation.git
   cd qa-automation
   ```

2. **Install project dependencies:**
   ```bash
   npm install
   ```

3. **Install Playwright browser binaries:**
   ```bash
   npx playwright install
   ```

---

## 🧪 Running Tests

### Run all tests in headless mode:
```bash
npx playwright test
```

### Run tests in headed mode (opens visual browser):
```bash
npx playwright test --headed
```

### Run tests in interactive UI mode:
```bash
npx playwright test --ui
```

### View test execution reports:
```bash
npx playwright show-report
```

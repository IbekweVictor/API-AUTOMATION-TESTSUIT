md
# 🔍 API Test Automation Framework – Gin & Juice E-commerce Platform

## 📌 Project Summary
This project is a **REST API automation testing framework** built to validate the backend services of the **Gin & Juice e-commerce website**.

🌐 **Website under test:** https://ginandjuice.shop

The framework focuses on ensuring the reliability, correctness, and performance of core business APIs using **Python**, **Pytest**, and **Requests**.

It is designed following **industry best practices** for:
- API test automation
- CI/CD integration
- Scalable test architecture
- Professional test reporting

---

## 🧰 Technical Skills & Tools
**Languages & Frameworks**
- Python
- Pytest (test framework)
- RESTful API testing

**Libraries & Tools**
- Requests (HTTP client)
- Allure Reports (test reporting)
- Logging (debugging & traceability)

**DevOps / CI**
- Jenkins (CI/CD pipeline)
- Git & GitHub

---

## 📂 Test Coverage
This test suite validates key backend workflows for the Gin & Juice platform, including:

- Homepage & service availability
- User authentication (login)
- Product listing and retrieval
- Cart operations
- Checkout and order flow
- API response validation (status codes, payloads, headers)

---

## 🗂️ Project Structure

```

├── tests/                      # Feature-based API test cases
│   ├── test_homepage.py
│   ├── test_login.py
│   ├── test_products.py
│   ├── test_cart_checkout.py
│
├── utils/                      # Reusable helper modules
│   ├── config.py               # Environment & base URL config
│   ├── logger.py               # Centralized logging
│
├── reports/
│   └── allure-results/         # Allure test execution results
│
├── allure-report/              # Generated HTML reports
├── conftest.py                 # Pytest fixtures & setup
├── pytest.ini                  # Pytest configuration
├── requirements.txt            # Project dependencies
├── Jenkinsfile                 # CI/CD pipeline configuration
└── README.md

````

---

## ▶️ How to Run the Tests

### 1️⃣ Clone Repository
```bash
git clone https://github.com/IbekweVictor/API-AUTOMATION-TESTSUIT.git
cd API-AUTOMATION-TESTSUIT
````

### 2️⃣ Set Up Virtual Environment

```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🧪 Execute API Tests

Run all tests:

```bash
pytest
```

Run tests with reporting enabled:

```bash
pytest --alluredir=reports/allure-results
```

---

## 📊 Test Reporting (Allure)

Generate and view interactive test reports:

```bash
allure serve reports/allure-results
```

Reports include:

* Test execution results
* Request & response logs
* Failure analysis
* Historical trends

---

## 🔄 CI/CD Pipeline

This framework includes a **Jenkins CI pipeline** that:

* Runs API tests automatically
* Validates backend services on every build
* Supports regression testing workflows

---

## 🎯 Why This Project Matters

This project demonstrates:

* API automation testing expertise
* REST API validation skills
* Pytest framework design and usage
* CI/CD integration experience
* Real-world e-commerce backend testing against a live production website

\# 🧪 Lab 16: GitHub Actions CI for Python App



This is a simple Python application with automated CI (Continuous Integration) using \*\*GitHub Actions\*\*. Every push and pull request to the `main` branch triggers a workflow that installs dependencies, runs unit tests, and ensures code quality.



---



\## 📁 Project Structure





---



\## ⚙️ GitHub Actions Workflow



The CI pipeline:



\- Triggers on `push` or `pull\_request` to the `main` branch

\- Sets up Python 3.10 on Ubuntu

\- Installs dependencies using `pip`

\- Runs tests using `pytest`



> File: `.github/workflows/python-ci.yml`



---



\## 🚀 How to Use



\### 1. Clone the repo



```bash

git clone https://github.com/<your-username>/ci-cd-labs.git

cd ci-cd-labs




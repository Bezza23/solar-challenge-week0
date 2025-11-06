# solar-challenge-week0

## Project Setup Guide

This project demonstrates how to set up a Python development environment with a virtual environment, dependencies, and continuous integration using GitHub Actions.

---

## 🚀 How to Reproduce the Environment

Follow these steps to reproduce the same environment locally:

### 1. Clone the Repository
```bash
git clone <your-repo-url>
cd <your-repo-folder>
```
### 2. Create Setup Task Branch

```bash
git branch setup-task
```

### 3. Checkout the Setup Branch 

```bash
git checkout setup-task
```

### 4. Create and Activate a Virtual Environment

```bash
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

## 🔄 Merge Instructions

Once everything is working:

### 1. Commit and push your branch

```bash
git add .
git commit -m "docs: complete README with environment setup instructions"
git push origin setup-task
```

### 2. On GitHub, open a Pull Request from setup-task → main

### 3. Review the changes and merge the PR once all checks pass

## 📁 Project Structure

```bash
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       ├── unittests.yml
│       └── ci.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md
```








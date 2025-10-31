# 🤝 Contributing to MickTrace

First off — thank you for taking the time to contribute to **MickTrace**! 🎉  
Your help is what makes this project better for everyone.

This guide outlines the process for contributing code, improving documentation, and reporting issues — so that we maintain a smooth and collaborative workflow.

---

## 🌍 Code of Conduct

Please read and follow our [Code of Conduct](./CODE_OF_CONDUCT.md) before contributing.  
It helps ensure that our community remains **open, inclusive, and respectful**.

---

## 🧠 Getting Started

### 1. Fork the Repository

Click the **“Fork”** button on the top-right of this page to create your own copy of the repository.

### 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/MickTrace.git
cd MickTrace

3. Create a New Branch

Create a branch that describes your feature or fix:

git checkout -b feature/add-new-logger
# or
git checkout -b fix/log-parsing-issue

4. Make Your Changes

Please follow the project’s existing code style and folder structure.

Keep your commits atomic (one logical change per commit) and use clear commit messages, e.g.:

feat: add custom JSON logging formatter
fix: handle invalid trace context gracefully
docs: update usage example for LogStream

5. Test Your Changes

If applicable, run all tests to ensure stability before submitting a PR.

pytest

> ✅ Make sure all tests pass before pushing changes.



6. Push and Submit a Pull Request

Push your branch and open a Pull Request (PR) to the main branch:

git push origin feature/add-new-logger

Then, go to your fork on GitHub → Compare & Pull Request.

Describe your changes clearly and link any related issues.


---

🧰 Development Setup

To run MickTrace locally:

```
# Clone repo
git clone https://github.com/ajayagrawalgit/MickTrace.git
cd MickTrace

# Install dependencies
pip install -r requirements.txt

# Run local test or dev build
pytest
```

> 💡 Tip: Use a virtual environment (python -m venv venv) to avoid dependency conflicts.




---

📚 Style Guidelines

Follow PEP 8 conventions for Python code

Write docstrings for all public functions and classes

Use type hints wherever possible

Keep function names descriptive but concise

Avoid hardcoding values — prefer configuration constants

Keep PRs focused and small for easier review



---

🪲 Reporting Bugs

If you find a bug, please open an issue using this template:

Title:

> [BUG] Log output not appearing in console



Description:

> Explain what happened and what you expected to happen.



Steps to Reproduce:

> 1. Run example.py


2. Observe missing output in console





Environment:

> OS: Ubuntu 22.04

Python: 3.12

MickTrace: 1.2.0




Before submitting, please:

Search existing issues to avoid duplicates

Include relevant logs or screenshots if possible



---

🚀 Feature Requests

We love new ideas!
If you’d like to suggest a feature, open an issue using the “Feature Request” template and describe:

The problem it solves

Example use cases

Potential API or configuration changes



---

🧩 Pull Request Review Process

1. Each PR is reviewed by a maintainer.


2. Requested changes must be addressed before merging.


3. Once approved, the PR will be squashed and merged into main.


4. CI/CD checks must pass before merge approval.




---

🛡️ Security Disclosure

If you discover a security vulnerability, please do not open a public issue.
Instead, email the maintainers directly at:

📧 ajayagrawalgit@gmail.com

We’ll investigate and resolve it as quickly as possible.
For more details, see our Security Policy.


---

🧠 Need Help?

If you’re unsure about anything, feel free to:

Open a GitHub Discussion

Ask questions via Issues

Or email the maintainers directly



---

Thank you for contributing to MickTrace! 💙
Your input helps us build a powerful, developer-friendly logging system for Python applications.
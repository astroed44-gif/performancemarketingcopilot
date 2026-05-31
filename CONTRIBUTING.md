# Contributing to Performance Marketing Copilot

First off, thank you for taking the time to contribute! 🎉 We welcome contributions from developers, marketers, data analysts, and AI enthusiasts of all skill levels.

By contributing to this project, you help make multi-agent marketing analytics accessible to everyone. Please read through these guidelines to ensure a smooth contribution process.

---

## 🗺️ How Can I Contribute?

### 1. Reporting Bugs
*   Check the [Issues](https://github.com/astroed44-gif/performancemarketingcopilot/issues) tab to see if the bug has already been reported.
*   If not, open a new issue. Include:
    *   A clear, descriptive title.
    *   Steps to reproduce the bug.
    *   Expected vs. actual behavior.
    *   Screenshots, terminal logs, or code snippets where applicable.

### 2. Suggesting Features
*   Open a new issue describing your idea.
*   Explain *why* this feature is useful and *how* it should work.
*   If you'd like to implement it yourself, mention that in the issue so we can assign it to you!

### 3. Submitting Pull Requests (PRs)
*   Fork the repository and create your branch from `main`.
*   Keep your changes focused. If you are fixing a bug and adding a feature, please submit them as separate PRs.
*   Ensure your code matches the existing style and is well-documented.

---

## 🛠️ Local Development Setup

To set up the project on your machine, follow these steps:

### 1. Prerequisites
Ensure you have the following installed:
*   Python 3.9 or higher
*   Git

### 2. Setup Guide
1.  **Fork & Clone the repository:**
    ```bash
    git clone https://github.com/YOUR-USERNAME/performancemarketingcopilot.git
    cd performancemarketingcopilot
    ```

2.  **Create a Virtual Environment:**
    ```bash
    # On macOS/Linux
    python3 -m venv .venv
    source .venv/bin/activate

    # On Windows
    python -m venv .venv
    .venv\Scripts\activate
    ```

3.  **Install Dependencies:**
    ```bash
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

4.  **Set Up Environment Variables:**
    Create a `.env` file in the root directory:
    ```env
    OPENAI_API_KEY=your_openai_api_key_here
    ```

5.  **Run the App locally:**
    ```bash
    python3 app.py
    ```
    Open `http://localhost:5000` in your browser.

---

## 🎨 Style Guide & Code Standards

### Python (Backend)
*   Follow [PEP 8](https://peps.python.org/pep-0008/) style guidelines.
*   Use descriptive variable and function names.
*   Document new specialist agents or tools with clean docstrings.

### JavaScript (Frontend)
*   Write modular, readable code in `static/` scripts.
*   Ensure visual components are responsive and clean.
*   Comment on complex UI rendering logic.

---

## 🤝 Code of Conduct
We want to keep our community safe, inclusive, and friendly. Please review our [Code of Conduct](CODE_OF_CONDUCT.md) before participating.

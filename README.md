# Code with AI: The AI Architect 🚀

## Course Overview
Welcome to **AI Powered Python**. This course is designed to transform you from a traditional coder into an **AI Architect**. We focus on high-speed development using AI-driven environments to build professional, data-intensive applications.

### Learning Outcomes
* [cite_start]**Master AI Environments:** Configure and navigate cloud-based development using GitHub Codespaces and GitHub Copilot[cite: 9, 17].
* [cite_start]**Synthetic Data Engineering:** Programmatically generate complex, realistic datasets to simulate real-world scenarios[cite: 10, 24].
* [cite_start]**Professional Workflow:** Implement industry-standard version control and repository hygiene[cite: 11, 30].

---

## Assignment 1: The SalesSim Data Engine
**Scenario:** You have been hired as a Data Engineer for a retail firm. Your first task is to architect the foundation of their Sales Analytics Dashboard. While we built a health tracker in class, you must now apply those same principles to **Retail Sales Data**.

### Technical Requirements
Your repository must fulfill the following architecture:

1.  [cite_start]**Folder Structure:** * `scripts/`: To hold your generation logic[cite: 19].
    * [cite_start]`raw_data/`: To store the generated output[cite: 19].
    * [cite_start]`tests/`: Pre-configured for auto-grading[cite: 50].

2.  **Data Generation Task:**
    * [cite_start]Create a file named `scripts/generate_sales.py`[cite: 23].
    * [cite_start]Use **GitHub Copilot** to write a script that generates a CSV named `sales_data.csv` in the `raw_data/` folder[cite: 31].
    * [cite_start]**Data Specifications:** 365 rows, columns for `Date`, `Product_ID` (101-120), `Units_Sold`, and `Revenue`[cite: 24, 25].
    * [cite_start]**Critical Constraint:** You must introduce **8% missing values (NaN)** randomly to simulate POS system sync errors[cite: 26].

3.  **Repository Hygiene:**
    * [cite_start]Generate a `.gitignore` file using AI to ensure no system junk or CSV files are tracked in your final commit[cite: 30].

### How to Submit
1.  Launch your **GitHub Codespace**.
2.  Complete the tasks using **Copilot Chat**.
3.  Commit your changes: `git commit -m "Complete Assignment 1"`.
4.  Push to GitHub: `git push origin main`.
5.  **Check your Grade:** Go to the "Actions" tab in your repo. [cite_start]If you followed the logic correctly, the Autograder will give you a green checkmark and 100 points![cite: 102, 120].

---
*Built with ❤️ for the Code with AI Course at Saras AI Institute.*

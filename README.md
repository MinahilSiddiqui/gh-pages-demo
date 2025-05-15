# GitHub Pages Demo

This repository contains a static website.

## View the Site
[Open the website in a new tab](https://<your-github-username>.github.io/gh-pages-demo/)  

## Contents
- `src/`: The folder containing the website's files.
  - [`index.html`](https://<your-github-username>.github.io/gh-pages-demo/): The main HTML file.
# Budget Tracker

This project is a simple web-based **Budget Tracker** application that allows users to manage their income and expenses. It is a lightweight tool for tracking financial transactions and calculating the remaining balance dynamically.

## Purpose of the Project
The purpose of this project is to:
1. Demonstrate the deployment of a static website using **GitHub Pages** and **GitHub Actions**.
2. Showcase the use of workflows to automate the deployment process whenever changes are pushed to the main branch.
3. Provide a hands-on example of how to create a functional and user-friendly budget tracker using basic web development technologies (HTML, CSS, and JavaScript).

### Workflow Overview
- **Trigger:** The deployment workflow is triggered whenever changes are pushed to the `main` branch.
- **Steps:**
  1. The source code is checked out using the `actions/checkout` action.
  2. Static files are prepared for deployment.
  3. The `/actions-gh-pages` action is used to publish the website to the `gh-pages` branch.

## Features
- **Dynamic Transaction Management:** Add income and expenses dynamically to update your balance in real time.
- **Visual Balance Display:** Clearly shows total income, total expenses, and the current balance.
- **Categorized Transactions:** Transactions are categorized as either income or expenses and displayed accordingly.
- **Interactive Form:** Users can input transaction descriptions, amounts, and select the type (income or expense) through an intuitive form.

## How It Works
1. **Add a Transaction:**
   - Enter a description for the transaction (e.g., "Salary" or "Groceries").
   - Specify the amount (e.g., `100.00` for income or `50.00` for expenses).
   - Choose whether the transaction is an income or an expense.
   - Click "Add Transaction" to record it.

2. **View Transactions:**
   - All transactions are displayed in a list, with income transactions highlighted in green and expenses in red.
   - The net balance, total income, and total expenses are updated automatically after each transaction.

3. **Live Updates:**
   - The application recalculates and displays the balance, total income, and total expenses dynamically.

## Deployment Process
The website is deployed to **GitHub Pages** using an automated workflow configured with **GitHub Actions**.

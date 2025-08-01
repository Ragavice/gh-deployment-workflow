# gh-deployment-workflow 

This project demonstrates how to deploy a static website to **GitHub Pages** using **GitHub Actions**.  
It sets up a basic **CI/CD pipeline** that only deploys changes when the `index.html` file is modified on the `main` branch.

---

##  Project Structure

---

## ⚙️ How It Works

- A push to the `main` branch triggers the workflow.
- The workflow **only runs when `index.html` is changed**.
- If triggered, it pushes the contents of the repo to the `gh-pages` branch.
- GitHub Pages is configured to serve the website from `gh-pages`.

---

## https://roadmap.sh/projects/github-actions-deployment-workflow

 [Click here to view the deployed website](https://ragavice.github.io/gh-deployment-workflow/)

---

## 🛠 Technologies Used

- **HTML**
- **GitHub Actions**
- **GitHub Pages**

---

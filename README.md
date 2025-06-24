# GitHub Actions Workflow: Node.js CI

This project demonstrates a basic GitHub Actions workflow that sets up a Node.js environment and logs a message to the console.

## 🔧 What It Does

- Initializes a GitHub Actions workflow on push or manual trigger.
- Sets up a Node.js 18 environment.
- Logs the message:  
  **"Hello from @rohan090987"**

## 📂 Project Structure

.github/
└── workflows/
└── node-pipeline.yml


## 🚀 How It Works

The workflow is defined in `.github/workflows/node-pipeline.yml` and includes the following steps:

1. **Checkout the repository**
2. **Setup Node.js using `actions/setup-node@v3`**
3. **Print a custom greeting message**

## 📸 Output Example (in Actions tab)


## ▶️ Triggering the Workflow

You can:
- Push a change to the `main` branch
- Or go to the **Actions** tab and click **"Run workflow"**

## 🟢 Live Status

[![Node.js CI](https://github.com/rohan090987/Build-a-GitHub-Actions-Pipeline/actions/workflows/node-pipeline.yml/badge.svg)](https://github.com/rohan090987/Build-a-GitHub-Actions-Pipeline/actions)


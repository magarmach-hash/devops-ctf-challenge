# 🏗️ Challenge: The Poisoned Pipeline

Welcome to the internal repo for **SecureCorp**. Our lead DevOps engineer just set up a new CI/CD pipeline using GitHub Actions. They claim that because they use `secrets`, no one can see our production flags.

### 🚩 Your Goal
Extract the value of the secret environment variable `PROD_FLAG`.

### 🕵️ Constraints
- You do **not** have write access to this repository.
- You must work via a **Fork** and **Pull Request**.
- You must find a way to make the automated "Production CI" workflow reveal the secret in its logs.

### 💡 Hint
Look closely at how the workflow triggers and what it executes. If you can control the code that runs during a build, can you control what it prints?

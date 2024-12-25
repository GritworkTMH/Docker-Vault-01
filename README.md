# Docker-Vault-01

A project to implement dynamic secrets management using Docker and HashiCorp Vault. The goal is to ensure that all identities are authenticated and authorized before granting access, and to enforce dynamic secrets with specific lifetimes, auto-generation, and expiration.

---

## Objectives
- Authenticate and authorize identities before granting access.
- Implement dynamic secrets that:
  - Have a defined lifetime.
  - Are auto-generated.
  - Automatically expire after their lifetime.

---

## Setting Up GitHub Repository
To set up and manage this project using GitHub, follow these steps:

1. Create a new repository on GitHub: [test1](https://github.com/GritworkTMH/test1.git)
2. Run the following commands in your terminal:

```bash
# Create a README.md file and initialize the repository
echo "# Docker-Vault-01" >> README.md
git init
git add README.md
git commit -m "first commit"

# Set the default branch to main and add the remote origin
git branch -M main
git remote add origin https://github.com/GritworkTMH/test1.git

# Push the changes to the GitHub repository
git push -u origin main

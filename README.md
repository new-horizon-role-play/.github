> ### DO NOT DELETE THIS FILE OR ANY `.GIT`/`.GITIGNORE` FILE!


# New Horizon Roleplay
> ### Development Server
---
Welcome to the **New Horizon Roleplay** development environment! This repository contains all necessary files and configurations for developing, testing, and improving the server. Please read this document carefully before making any modifications.

---

## 📌 Server Overview

The **New Horizon Roleplay Development Server** is a controlled environment used for testing new scripts, features, and configurations before deploying them to the live server. Our goal is to ensure stability, performance, and the best possible experience for our community.

---

## 🚀 Requirements

Ensure you have the following installed before running the server:
- **[FiveM Server Artifacts](https://runtime.fivem.net/artifacts/fivem/)** (Latest Stable)
- **[FXServer](https://fivem.net/)** (Windows or Linux)
- **GitHub Desktop** (For managing version control)
- **Visual Studio Code** or a similar editor

---

## 🔧 Development Guidelines

### ✅ **Version Control**
- Always create a new branch when developing a feature.
- Use descriptive commit messages.
- Merge changes into `main` or `staging` only after testing.

### 📝 **Coding Standards**
- Follow **QBCore** structure and best practices.
- Comment your code thoroughly.
- Avoid unnecessary loops or heavy client-side operations.

### 📌 **Testing Procedures**
- Use a separate character for testing.
- Log any errors in `logs/` and report them.
- Test new scripts in `staging` before pushing to `production`.

### 🛠 **Script Development**
- Place custom scripts in `resources/[custom]/`
- Prefix scripts with `nhrp-` to identify server-specific modifications.

---

## 🔥 Important Resources

### 📂 **Folder Structure** *(Not Accurate as of 4-9-2025)*

📦 New Horizon Roleplay-DevServer ┣ 📂 resources ┃ ┣ 📂 [qb-core]  # Core framework ┃ ┣ 📂 [custom]   # Custom scripts & modifications ┃ ┣ 📂 [maps]     # Server-specific map modifications ┃ ┣ 📂 [jobs]     # Custom jobs & businesses ┃ ┣ 📂 [vehicles] # Custom & VIP vehicles ┃ ┗ 📂 [addons]   # Miscellaneous resources ┣ 📂 logs         # Server logs & error tracking ┣ 📜 server.cfg   # Server configuration file ┣ 📜 run.sh       # Server start script (Linux) ┣ 📜 run.cmd      # Server start script (Windows) ┗ 📜 README.md    # This file

---

## 🔑 Access Control
- Only **approved developers** have access to the development server.
- Do not share credentials or access tokens.
- Report any security concerns immediately.

---

## 🚨 Troubleshooting
### ❓ **Common Issues**
| Issue | Solution |
|-------|---------|
| Server won't start | Check `server.cfg` for errors, ensure all dependencies are installed |
| Scripts not loading | Ensure scripts are started in `server.cfg` |
| Unexpected crashes | Check the `logs/` folder for debugging information |

---

## 🛡️ Contribution Guidelines
1. **Create a new branch** in GitHub Desktop before making changes.
2. **Commit changes** with clear descriptions.
3. **Test your changes** in a local environment.
4. **Push changes** to the repository and create a pull request to `staging` for review.

---

## 🎯 Contact & Support
- **Discord:** [New Horizon Roleplay Community](https://discord.gg/NewHorizon-RP)
- **Documentation:** Available in the `docs/` folder.
- **Bug Reports:** Submit via GitHub Issues.

---

### 🚀 Keep Innovating & Happy Developing!
**New Horizon Roleplay Dev Team**

# 🚀 Introduction to Use GitHub (SNU-WRL)
Welcome to the **SNU-WRL** official organization! This guide helps members understand how to manage and contribute to our repositories efficiently.

## Content

1. Creating & Importing a Repository
2. 
3. README file templete

---

## 1. Creating & Importing a Repository

Before creating a repository, choose the right method for your project:
* **Method A (Create New):** Start a brand new project from scratch directly in the organization.
* **Method B (Fork/Copy):** Bring an existing project from your personal account into the organization.

---

### 🟢 Method A: How to Create a New Repository Directly
Use this when you are **starting a project without an existing GitHub repository**, or when you want to start a completely new codebase from scratch.

1. Click the **"New"** green button on the organization main page.
2. Select the owner as **"SNU-WRL"** and type the repository name following **our naming convention**.
3. Choose visibility as **"Private"**. *(Note: You can change this to **Public** later if needed.)*
4. Check **"Add a README file"**. It is also recommended to add a **.gitignore** file and a **license**.
5. Click **"Create repository"**.

---

### 🔵 Method B: How to Fork an Existing Repository
Use this when you want to move or copy your **personal repository** to the organization while keeping them connected.
*(Note: This maintains a link between your personal account and the organization account, allowing you to sync updates later.)*

1. Go to your personal GitHub repository.
2. Click the **"Fork"** button in the top-right corner.
3. Select the owner as **"SNU-WRL"**.
4. If you want to copy other branches as well, uncheck **"Copy the main branch only".**
5. Click **"Create fork"**.

---

### 🏷 Name of the Repository (Naming Convention)
To keep our organization organized, please follow our naming rules:
* `robot-***` : Robotics hardware or control source code (e.g., `robot-shoe-control`)
* `algorithm-***` : Core algorithm testing and research (e.g., `algorithm-imu-vqf`)
* `study-***` : Internal seminars, papers, and learning logs.

### 📄 README File Template
Every repository **MUST** include a `README.md` file at the root. Please include:
1. **Project Description**: What is this project for?
2. **Prerequisites**: Required OS, ROS version, Python version, etc.
3. **How to Run**: Step-by-step commands to execute the code.

---

## 🌿 2. Git Workflow (How to Commit & Collaborate)

### 📌 Branch Strategy
* `main` : Stable code that is fully tested. (Do not commit directly to `main`!)
* `feature/***` : Develop new features or research specific topics here (e.g., `feature/vqf-optimization`).

### 🤝 Pull Request (PR) & Review
* Once your feature is ready, open a **Pull Request** to the `main` branch.
* At least **1 other member** must review and approve your code before merging.

---
💡 *If you have any questions about this guide, please open an Issue or contact the administrator.*

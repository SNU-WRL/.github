# 🚀 Introduction to Use GitHub (SNU-WRL)
Welcome to the **SNU-WRL** official organization! This guide helps members understand how to manage and contribute to our repositories efficiently.

---

## 1. Creating repository

### 💡 How to Create a Repository
1. Click the **"New"** green button on the organization main page.
2. Select the owner as **SNU-WRL**.
3. Choose visibility between **Public** (open to anyone) or **Private** (internal research only).

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

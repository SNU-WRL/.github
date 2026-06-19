# 🚀 Introduction to Use GitHub (SNU-WRL)
Welcome to the **SNU-WRL** official organization! This guide helps members understand how to manage and contribute to our repositories efficiently.

## Content

1. Creating & Importing a Repository
2. Naming convention
3. README.md file templete
4. Managing Repositories via Git Commands

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

## 2. Naming convention
To keep our organization organized and searchable, please follow this naming structure when creating or importing a repository.

- Use hyphens (-) to separate words.
- Every repository name must start with one of the three prefixes: Robot-, Data-, or Algo-.
- The *** suffix is optional. Add it only if you need to provide more context, such as the programming language used or a sub-task name.

### 1. Robot-[Hardward name]-***
- **Description:** Source code used to control, drive, or operate robotics hardware (including firmware, ROS packages, and actuators).
- Examples: Robot-Slip_Motor_Shoe, Robot-Wearable_Robot-Hip_Flexion_Control

### 2. Data-[Sensor or Equipment name]-***
- **Description:** Source code dedicated to analyzing, processing, filtering, or visualizing data collected from specific sensors or lab equipment.
- Examples: Data-IMU-Analysis_Gait_Metric-Python, Data-Mocap-Analysis_Gait_Metric-Matlab, Data-WIM

### 3. Algo-[Purpose of algorithm or Algorithm objective]-***
- **Description:** Source code focusing on the development, implementation, and testing of core algorithms, estimation models, or signal processing methods (independent of specific hardware setups).
- Examples: Algo-VQF, Algo-Gait_Event_Detection

## 3. README.md file templete

## 4. Managing Repositories via Git Commands

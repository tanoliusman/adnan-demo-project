# 🚀 React Project Kickstart: The Digital Resume Project

Welcome, Adnan! You are about to build your first React application. [cite_start]To make this meaningful, we are building a digital version of a **Principal Software Engineer's resume**[cite: 1, 2]. [cite_start]This project will teach you how to translate 10+ years of high-level development experience into a modern web interface[cite: 4].

---

## 🛠 Step 1: The Environment Setup
Before we code, we need to prepare your machine.

1.  **Install Node.js**: Download the **LTS version** from [nodejs.org](https://nodejs.org/).
2.  **Install VS Code**: Your IDE for this project [code.visualstudio.com](https://code.visualstudio.com/).
3.  **Install Git**: Ensure Git is installed on your machine from [git-scm.com](https://git-scm.com/).

---

## 🏗 Step 2: Create & Connect to GitHub
Follow these steps to create your project and link it to the **Adnan Demo Project** repository.

1.  **Open the Terminal** in VS Code (`Ctrl + ` `).
2.  **Generate Project**: 
    ```bash
    npm create vite@latest adnan-demo-project -- --template react
    ```
3.  **Enter the Folder**: 
    ```bash
    cd adnan-demo-project
    ```
4.  **Initialize Git & Link Repository**:
    Run these commands one by one to connect your local code to the GitHub repository:
    ```bash
    git init
    git remote add origin [https://github.com/tanoliusman/adnan-demo-project](https://github.com/tanoliusman/adnan-demo-project)
    git add .
    git commit -m "Initial React setup with Vite"
    git branch -M main
    git push -u origin main
    ```

---

## 🏃 Step 3: Launch the App
1.  **Install Libraries**:
    ```bash
    npm install
    ```
2.  **Start Development Mode**:
    ```bash
    npm run dev
    ```
3.  **View it**: Open the link provided in the terminal (usually `http://localhost:5173`).

---

## 🎯 The Assignment: "The Usman Ali Resume"
[cite_start]Your goal is to replace the default Vite code with the professional details of **Usman Ali**[cite: 1]:

### Key Data to Include:
* [cite_start]**Header**: Name: Usman Ali [cite: 1] | [cite_start]Title: Principal Software Engineer[cite: 2].
* [cite_start]**Contact**: Riyadh, Saudi Arabia [cite: 14] [cite_start]| tanoliusmanali@email.com[cite: 13].
* [cite_start]**Top Skillset**: Java 17, Spring Boot, Microservices, and Docker[cite: 10].
* **Core Experience Highlights**: 
    * [cite_start]**Senior Software Engineer at Seera (2022-Now)**: Building security systems with Spring OAuth 2.1 for 3 million users[cite: 16, 17, 19].
    * [cite_start]**Principal Software Engineer at Matas A/S (2018-2022)**: Designing microservices on Azure from monolithic applications[cite: 23, 24, 26].
* [cite_start]**Education**: Masters in Computer Science from Fast University Karachi[cite: 48].

### Professional Guidance:
* [cite_start]**Maintainable Code**: Aim for "robust, maintainable code" as highlighted in the profile[cite: 8]. Keep your React components small and clean.
* [cite_start]**Scalable Thinking**: As someone who architects "scalable solutions," think about how you would make this resume easy to update in the future[cite: 5].
* **Deployment**: Once finished, run `git add .`, `git commit -m "Completed Resume"`, and `git push` to save your work to GitHub.

---

## ✅ Final Checklist
* [ ] Git initialized and linked to the **adnan-demo-project** repository.
* [ ] `npm install` completed without errors.
* [ ] Local server running and displaying the resume.
* [ ] Code successfully pushed to GitHub.

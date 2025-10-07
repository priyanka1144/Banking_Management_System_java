# 🏦 Banking Management System

A **secure and user-friendly** Java-based banking management system built with Swing, designed for account management, transactions, and auditing.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)  
[![Platform: Windows, macOS, Linux](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-green)](#installation)  
[![Java](https://img.shields.io/badge/Language-Java-orange.svg)](https://www.java.com/)  
[![IDE: NetBeans](https://img.shields.io/badge/IDE-NetBeans-yellow.svg)](https://netbeans.apache.org/)

---

## 📖 Table of Contents
- [🔹 Features](#-features)
- [🔹 Installation Guide](#-installation-guide)
- [🔹 Usage](#-usage)
- [🔹 Technical Highlights](#-technical-highlights)
- [🔹 Limitations](#-limitations)
- [🔹 How to Upload to GitHub](#-how-to-upload-to-github)
- [🔹 Contribution](#-contribution)
- [🔹 License](#-license)

---

## 🔹 Features
✅ **Account Management**: Create, update, delete accounts with name, phone, NID, DOB, and balance.  
✅ **Transactions**: Deposit, withdraw (with insufficient funds check), and balance inquiry.  
✅ **Student Feature**: Yes/No option for student accounts.  
✅ **Audit Logging**: Tracks all actions (e.g., account creation, transactions).  
✅ **Secure Login**: Username/password with 3-attempt limit (Default: `priyanka12$`, `Priyanka12$$`).  
✅ **Cross-Platform**: Runs on Windows, macOS, and Linux with NetBeans.  

---

## 🔹 Installation Guide

### 🖥 Windows Installation
1. **Install JDK & NetBeans**
   - Download JDK from [oracle.com](https://www.oracle.com/java/technologies/javase-downloads.html).
   - Install Apache NetBeans from [netbeans.apache.org](https://netbeans.apache.org/download/index.html).
2. **Open Project**
   - File > Open Project > Select the `Updateproject` folder.
3. **Run**
   - Right-click project > Run (or Shift+F6).

### 🍏 macOS Installation
1. **Install JDK & NetBeans**
   - Follow the same JDK and NetBeans links as above.
2. **Open & Run**
   - Same as Windows steps.

### 🐧 Linux Installation
1. **Install JDK & NetBeans**
   - `sudo apt update && sudo apt install openjdk-11-jdk`
   - Download and install NetBeans manually.
2. **Open & Run**
   - Same as above.

---

## 🔹 Usage
1. **Login**: Use default credentials to access the system.
2. **Create Account**: Fill fields (e.g., name, phone), check "Student" if applicable, click "Create Account".
3. **Transactions**: Enter account number and amount for deposit/withdrawal.
4. **View Logs**: Use "View Audit Logs" or "All Accounts" for records.

---

## 🔹 Technical Highlights
🔧 **Swing GUI**: Interactive interface with color-coded design (blue, white, gold).  
🔒 **Validation**: Checks for valid phone (11 digits, starts with 01), NID (10 digits), and DOB (DD-MM-YYYY).  
📋 **In-Memory Storage**: Uses ArrayList for accounts, transactions, and audit logs.

---

## 🔹 Limitations
- **No Persistence**: Data resets on program close (no database).
- **Single User**: Limited to one login.
- **Offline Only**: No network support.

---

## 🔹 How to Upload to GitHub
1. **Install Git**:
   - Download from [git-scm.com](https://git-scm.com/downloads) and configure (`git config --global user.name "Your Name"`, `git config --global user.email "your@email.com"`).
2. **Initialize Git in NetBeans**:
   - Right-click project > **Team > Git > Initialize Repository**.
   - Add files: **Git > Add** > Select all > OK.
   - Commit: **Git > Commit** > Message "Initial commit" > Commit.
3. **Create GitHub Repo**:
   - Go to [github.com](https://github.com), click **+ > New repository**.
   - Name it "Banking-Management-System", keep empty, create.
4. **Push to GitHub**:
   - Right-click project > **Git > Remote > Push to Upstream**.
   - URL: `https://github.com/YOUR_USERNAME/Banking-Management-System.git`.
   - Use GitHub username and Personal Access Token (PAT) as password (get PAT from Settings > Developer settings > Personal access tokens > Generate new with repo scope).
   - Push and verify on GitHub.
5. **Add README**: Upload this file to the repo root.

---

## 🔹 Contribution
Fork this repo, submit pull requests, or open issues for improvements (e.g., database integration, GUI enhancements). Let’s build together! 🚀

---

## 🔹 License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 📌 Developed by: Priyanka Paul
**GitHub**: [@priyanka1144](https://github.com/priyanka1144)


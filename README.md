<div align="center">

# 🐂 TECH BULL FOR WINDOW

### Cyber Digital Tree — Educational Remote Administration & System Learning Project

<img src="https://github.com/KT-US/techbull4window/blob/96c4e58ae02a442352b9c34a8b60672e2e7744b1/tech_bull4_window_1.jpg" width="850"/>

![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-success)
![Language](https://img.shields.io/badge/C%2B%2B-blue)
![Status](https://img.shields.io/badge/Status-Stable-green)
![Purpose](https://img.shields.io/badge/Purpose-Education-orange)
![Encryption](https://img.shields.io/badge/Encryption-AES-red)

</div>

---

## 📌 Introduction

**Tech Bull for Window** is an educational project developed by **Cyber Digital Tree (CDT)**.

The purpose of this project is to help learners understand concepts used in:

* Remote administration
* Client–server communication
* File management workflows
* Directory traversal
* Multi-client handling
* Camera and multimedia functions
* System resource management

This project currently supports a **Windows client** and a **Linux server**, with future expansion planned.

---

## 🚀 Features

✔ One-to-One Client Handling  
✔ One-to-Many Client Handling  
✔ Directory Navigation  
✔ File Download Management  
✔ File Upload Management  
✔ AES Encrypted Communication  
✔ Camera Functions (Image Capture, Live Streaming)  
✔ File Searching by Name & Extension  
✔ Remote Command Execution  
✔ Hide/Unhide Application Icon  

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/KT-US/techbull4window.git
```

After downloading, you will find two files:

1. `TechBullServer.elf` - Linux Server
2. `Techbull4window.exe` - Windows Client

---

## 🖥️ Server Setup (Linux)

Give execution permission:

```bash
sudo chmod +x TechBullServer.elf
```

Run the server:

```bash
./TechBullServer.elf
```

After starting the server, the following interface will appear:

<img src="https://github.com/KT-US/techbull4window/blob/96c4e58ae02a442352b9c34a8b60672e2e7744b1/tech_bull4_window_2.jpg.png" width="800"/>

### Find Your Server IP

Run:

```bash
ifconfig
```

or

```bash
ip addr
```

Example:

```
192.168.x.x
```

This IP address will be required on the Windows client.

---

## 💻 Client Setup (Windows)

No installation is required. Simply copy `Techbull4window.exe` to the Windows machine and run it.

On first launch, the application creates:

```
techbull4windows_serverip.txt
```

**Application Icon:**

<img src="https://github.com/KT-US/techbull4window/blob/96c4e58ae02a442352b9c34a8b60672e2e7744b1/tech_bull4_window_3.jpg" width="200"/>

Open the file and enter your Linux server IP:

```
serveripaddress=192.168.x.x
```

Save the file (**Ctrl + S**) and close it. Within a few seconds, the client will automatically connect to the server.

---

## ✅ Successful Connection

Once connected, two command consoles will appear:

<img src="https://github.com/KT-US/techbull4window/blob/96c4e58ae02a442352b9c34a8b60672e2e7744b1/tech_bull4_window_4.jpg" width="800"/>

### Server Control Console

<img src="https://github.com/KT-US/techbull4window/blob/96c4e58ae02a442352b9c34a8b60672e2e7744b1/tech_bull4_window_5.png" width="600"/>

### Client Control Console

<img src="https://github.com/KT-US/techbull4window/blob/96c4e58ae02a442352b9c34a8b60672e2e7744b1/tech_bull4_window_6.jpg" width="600"/>

---

## 🏗 Architecture

```
┌──────────────┐           AES Encrypted            ┌──────────────┐
│ Linux Server │  <------------------------------> │ Windows Client│
└──────────────┘                                    └──────────────┘
```

---

## 🖥 Server Control Commands

| Command | Description |
|----------|-------------|
| 0 | Terminate Server |
| 1 | Show Help / Available Commands |
| 2 | List Connected Clients |
| 3 | Select a Specific Client |
| 4 | Client Connection History |
| 5 | Show Current Working Directory |
| 6 | Change Directory |
| 7 | List Directory Contents |

---

## 🎯 Client Control Commands

### Basic Commands

| Command | Description |
|----------|-------------|
| 0 | Help Menu |
| 1 | Disconnect / Terminate Specific Client |
| 2 | Operating System Information |
| 3 | Current Working Directory |
| 4 | List Directories |
| 5 | Change Directory |
| 6 | Root Directory |
| 7 | Directory Traversal |
| 8 | Search File/Directory by Name |
| 9 | Search Files by Extension |
| 14 | Hide Application Icon |
| 15 | Unhide Application Icon |

---

### 📥 Download Files (Command 10)

| Option | Description |
|--------|-------------|
| 1 | Download a specific file (exact filename with extension) |
| 2 | Download all files with a specific extension (.jpg, .png, .mp3, .mp4, .txt, .pdf, etc.) |

---

### 📸 Camera Functions (Command 11)

| Option | Description |
|--------|-------------|
| 1 | Check number of client cameras |
| 2 | Capture a Picture |
| 3 | Live Video Streaming |
| 4 | Terminate Camera Functionality |

---

### 🗑️ Search & Delete Operations

| Command | Description |
|----------|-------------|
| 12 | Search and Delete Directory or File by Name |
| 13 | Search and Delete File by Extension |

---

### 📤 Upload Data to Client (Command 16)

| Option | Description |
|--------|-------------|
| 0 | Help Menu |
| 1 | Check Server Current Working Directory |
| 2 | Change Server Directory |
| 3 | List Directories in Current Working Dir |
| 4 | Upload a Specific File |
| 5 | Upload All Files with Same Extension (.jpg, .png, .txt, .mp3, .mp4, etc.) |
| 6 | Check App Version and Update |
| 7 | Show Current App Version |
| 8 | Terminate Upload Process (Cannot go back) |

---

## 🔐 AES Encryption

Communication between the server and client is protected using the **AES (Advanced Encryption Standard)** algorithm.

This encryption helps secure data while it is transmitted between both endpoints.

---

## 🎥 Video Tutorials

Learn how to use **Tech Bull for Window** through practical demonstrations.

📺 **Cyber Digital Tree YouTube Channel** 👉 https://www.youtube.com/@CyberDigitalTree

Subscribe for:

* Tool demonstrations
* Setup tutorials
* Feature explanations
* Development updates

<a href="https://www.youtube.com/@CyberDigitalTree">
  <img src="https://img.shields.io/badge/Watch%20Tutorials-YouTube-red?style=for-the-badge&logo=youtube"/>
</a>

---

## ⚠ Disclaimer

This project is intended **strictly for educational use, authorized penetration testing, and remote administration of devices you own or have explicit permission to control**.

By using this software you agree:

* Not to access systems without permission
* To follow local and international laws
* To use the project responsibly

**Misuse of this tool is strictly prohibited.** The authors are not responsible for any damages, legal consequences, or unethical use of this software.

**THIS TOOL IS ONLY FOR EDUCATION PURPOSE**

---

<div align="center">

Made with ❤️ by **Cyber Digital Tree**

</div>

# How to install WSL 🚀
# WSL (Windows Subsystem for Linux)
WSL (Windows Subsystem for Linux) is a compatibility layer that allows users to run a Linux environment directly on Windows, without the need for a virtual machine or dual boot. It provides a native Linux experience within Windows, enabling developers to use Linux tools, utilities, and applications seamlessly.

 # Features of WSL
✔️ Run Linux on Windows – No need for a separate machine or virtual machine.
✔️ Fast Performance – Near-native performance as it runs directly on Windows kernel.
✔️ Access to Linux Tools – Use Bash, Git, Vim, Python, and other Linux utilities.
✔️ Supports GUI Apps – WSL 2 allows running Linux GUI apps with GPU acceleration.
✔️ Easy File Sharing – Access Windows files from Linux and vice versa.
✔️ Docker & AI Development – Works well with Docker, TensorFlow, and other tools.
# Versions of WSL
## 1️⃣ WSL 1 (Original Version)
Uses a compatibility layer to translate Linux system calls to Windows.
Faster file performance for Windows-based files.
Limited support for full Linux features (e.g., no full system call support).
 ## 2️⃣ WSL 2 (Improved Version)
Uses a real Linux kernel inside a lightweight virtual machine (VM).
Full Linux system call compatibility – supports Docker, GPU compute, etc.
Better overall performance but slightly slower file access to Windows folders.

# How to Install WSL on Windows
## Step 1: Enable WSL
Open PowerShell (Admin) or CMD and run:
## Installation 🔧
```bash
wsl --install
```
This installs WSL 2 with Ubuntu as the default distro.
# Step 2: Check Available Distros
```bash
wsl --list --online
```
# Step 3: Install a Linux Distro
To install a specific distro (e.g., Debian or Kali Linux):
```bash
wsl --set-version Ubuntu 2
```
# Step 4: Set WSL Version
To use WSL 2 for a distro:
```bash
wsl --set-version Ubuntu 2
```
# Step 5: Open WSL
Simply type:
```bash
wsl
```

# Common Use Cases for WSL
## 💻 Web Development – Run Linux-based servers, databases, and tools.
## 🐍 AI & Machine Learning – Use TensorFlow, PyTorch, Jupyter Notebook.
## 🐳 Docker & Containers – WSL 2 fully supports Docker.
## ⚙️ System Administration – Run Linux scripts and manage servers from Windows.

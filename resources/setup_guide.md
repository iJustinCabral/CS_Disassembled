# Environment Setup Guide

I teach using **macOS** and **Clang** C compiler.
You can use whatever OS you want, but you are responsible for translating the terminal commands.

## The Goal
By the end of this setup, you need two things working in your terminal:
1.  A C Compiler (Clang or GCC)
2.  A Debugger (LLDB or GDB)

---

## 🍎 macOS Users
You likely already have everything or just need the command line tools.
1.  Open Terminal.
2.  Type `clang --version`.
3.  If it asks to install "Command Line Tools," say **Yes**.
4.  **Debugger:** You will use `lldb` (it comes with Xcode tools).

## 🐧 Linux Users
You are on home turf.
1.  **Compiler:** Install GCC (`sudo apt install build-essential` or equivalent) OR Clang (`sudo apt install clang`).
2.  **Debugger:** Install `gdb` or `lldb`.

## 🪟 Windows Users (The Hard Mode)
Programming C on Windows is different. You have two main paths. **Choose one.**

### Path A: WSL2 (Recommended)
This installs a real Linux kernel inside Windows.
1.  Install **WSL2** (Ubuntu) from the Microsoft Store.
2.  Follow the **Linux** instructions above inside your WSL terminal.
3.  *Pro:* You can follow my video commands almost exactly.

### Path B: LLVM for Windows
1.  Download the **LLVM** installer (contains Clang).
2.  Add it to your PATH environment variable.
3.  **Debugger:** You might need to use the Visual Studio debugger or configure LLDB manually.
4.  *Warning:* If you choose this, you are on your own for setting up the environment.

---

## 🛠 The Editor
I use **Emacs**.
You can use VS Code, Vim, Sublime Text, or Notepad++.
**Requirement:** Just make sure you can edit text and run terminal commands.
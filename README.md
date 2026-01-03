# CS: Disassembled

**CS: Disassembled** is a 12-part engineering series designed to peel back the layers of abstraction in modern software. I plan to do my best in teaching how the ghost inside our machines work.

This repository contains the source code, labs, and "Artifacts" for the 2026 YouTube series.

---

## 🏴 The Philosophy

Modern programming education often treats the computer like a magic black box. You type high-level code, and magic happens. But when the magic breaks, you're often stranded in tutorial hell instead of building things. This course stands on three core pillars:

1.  **The Code (Abstraction):** We write C to solve a problem.
2.  **The Truth (Assembly):** We read the raw machine instructions to see what the CPU is actually doing.
3.  **The Proof (Debugger):** We watch the registers and memory change in real-time to prove our assumptions.

I do not want you to come out of this course as a "passenger" who rely on AI pilots but as a thinker who can solve hard problems using fundamental understandings. 
---

## 🗺 The Syllabus (2026 Roadmap)

We will build 12 specific "Artifacts"—system tools that expose how the computer works.

| Case File | Topic | The Artifact (Project) | Status |
| :--- | :--- | :--- | :--- |
| **01** | Bits, Integers & Overflow | **The Odometer** <br> *A visualizer for binary overflow.* | [ ] |
| **02** | Reading Memory | **The Hex Dumper** <br> *A tool to view raw bytes of any file.* | [ ] |
| **03** | The Stack & Scope | **The Crash Report** <br> *Forensic analysis of a stack smash.* | [ ] |
| **04** | Pointers & Addresses | **The Memory Spy** <br> *Scanning RAM to find hidden values.* | [ ] |
| **05** | Arrays & Buffers | **The Safe String Lib** <br> *Fixing C's biggest mistake.* | [ ] |
| **06** | The Heap (Malloc/Free) | **The Arena** <br> *Writing a custom memory allocator.* | [ ] |
| **07** | Structs & Alignment | **The Packer** <br> *Binary serialization tool.* | [ ] |
| **08** | File I/O & Persistence | **The Database** <br> *A raw binary key-value store.* | [ ] |
| **09** | Assembly & The CPU | **The Disassembler** <br> *Decoding machine code to text.* | [ ] |
| **10** | Terminal Control | **The Canvas** <br> *A raw-mode drawing library.* | [ ] |
| **11** | Data Structures | **The Gap Buffer** <br> *The engine for a text editor.* | [ ] |
| **12** | **Capstone** | **The Kilo Editor** <br> *A fully functional text editor in C.* | [ ] |

---

## 🛠 The Environment

**I use:**
* **OS:** macOS
* **Editor:** Emacs
* **Compiler:** Clang
* **Debugger:** LLDB

**You can use:**
Whatever you want. Windows, Linux, VS Code, Vim, Notepad.

**⚠️ The "Figure It Out" Rule:**
I will not hold your hand on environment setup. Part of being any kind of critical thinker is learning  how to configure your tools.
* If you are on Windows, I recommend **WSL2**.
* If you are stuck, read the [Setup Guide](./resources/setup_guide.md) for hints.
* If you are using GDB debugger instead of LLDB, use the [Debugger Rosetta Stone](./resources/debugger_cheatsheet.md).

---

## 📂 Repository Structure

Each module is organized as a "Case File":

* `source/`: The code I write during the video.
* `lab/`: **Your Homework.**
    * This contains a broken or incomplete program.
    * Your job is to fix it using the skills from the video.
    * *Do not look at the `solution` branch until you have tried.*

---

## 🤝 Contributing

This is a learning resource. If you find a bug in the code or a typo in the documentation, feel free to open a PR.

**License:** MIT
**Author:** Justin | Thinkr Labs# CS Disassembled
Computer Science taught through learning the C programming language, the use of debuggers, and understand assembly

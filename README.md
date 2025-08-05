# 📡 MiniTalk

**MiniTalk** is a simple client-server messaging system using only **UNIX signals**.  
This 42 project demonstrates inter-process communication using low-level signaling (`SIGUSR1`, `SIGUSR2`) to transmit strings from one process (client) to another (server) **bit by bit**.

![Language](https://img.shields.io/badge/C-100%25-blue)
![Signals](https://img.shields.io/badge/UNIX-Signals-purple)
![Status](https://img.shields.io/badge/Project-Done-success)

---

## 🧩 About

> MiniTalk is a proof-of-concept to show how signals (`SIGUSR1` and `SIGUSR2`) can be used for **bit-level communication** between 2 processes.

You write a **server** that listens for signals and a **client** that sends characters bit by bit.

No pipes, no sockets — just signals and patience. 😄

---

## 🚀 Features

- ✅ Pure **signal-based communication**
- ✅ Sends strings (with newline or null terminator)
- ✅ Can handle long messages
- ✅ Clean output with PID and status
- ✅ Works on **Linux/macOS**

---

## 🛠 Installation

```bash
git clone https://github.com/seeknoobwisdom/minitalk.git
cd minitalk
make

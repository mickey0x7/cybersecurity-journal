# 🛡️ Cybersecurity Journal

---

# 📅 Day 1 — 26 June 2026

**Focus:** Linux Basics • Networking • First Wargame (Bandit)

⏱️ **Time Spent:** ~2 Hours

---

## 🎯 Objectives

* Learn basic Linux commands
* Complete OverTheWire Bandit Level 0
* Begin networking fundamentals
* Set up cybersecurity learning accounts

---

## ✅ Completed

* Created accounts:

  * GitHub
  * LinkedIn
  * TryHackMe
  * Hack The Box Academy
* Used the same username across every platform.
* Practiced basic Linux commands.
* Learned how to edit and save files using `nano`.
* Completed **OverTheWire Bandit Level 0**.
* Finished the first **TryHackMe Networking** lesson.

---

## 📚 Key Concepts Learned

### 🌐 Internet History

* ARPANET was the foundation of today's Internet.
* Tim Berners-Lee later invented the **World Wide Web**, making the Internet much easier to access.

---

### 🌍 Network Addressing

| Concept         | Description                                          |
| --------------- | ---------------------------------------------------- |
| **MAC Address** | Permanent hardware identifier of a network interface |
| **IP Address**  | Logical address assigned on a network and can change |

---

### 🌐 IPv4 vs IPv6

| IPv4                | IPv6                              |
| ------------------- | --------------------------------- |
| 32-bit addressing   | 128-bit addressing                |
| Four octets (0–255) | Vastly larger address space       |
| Limited addresses   | Designed to solve IPv4 exhaustion |

---

### 🎭 Spoofing

Spoofing is the act of pretending to be another device or identity by forging information such as an IP or MAC address.

---

## 💻 Commands Practiced

```bash
pwd
ls
cd
cat
nano
ls -la
```

---

## ⚠️ Biggest Challenge

Saving and exiting `nano`.

### ✔️ Solution

```text
Ctrl + O
Enter
Ctrl + X
```

---

## 💭 Reflection

Today felt like the real beginning of my cybersecurity journey.

Everything was unfamiliar at first, but I completed every planned task without skipping the difficult parts. Learning how Linux works already feels different from simply using a computer.

---

## 🚀 Tomorrow

* [ ] Complete Bandit Levels 1–3
* [ ] Continue the TryHackMe Pre-Security path
* [ ] Practice more Linux commands

---

# 📅 Day 2 — 27 June 2026

**Focus:** Bandit Levels 1–3 • Computer Fundamentals

⏱️ **Time Spent:** ~1.5 Hours

---

## 🎯 Objectives

* Complete Bandit Levels 1–3
* Continue TryHackMe learning
* Improve Linux file handling

---

## ✅ Completed

* Solved **Bandit Level 1** (filename `-`)
* Solved **Bandit Level 2** (filename containing spaces)
* Solved **Bandit Level 3** (hidden file)
* Completed the TryHackMe room **Inside a Computer System**

> Planned networking rooms ("Intro to LAN" and "OSI Model") were unavailable because they are now premium content.

---

## 📚 Key Concepts Learned

### 📁 Linux File Handling

#### Level 1 — File Named `-`

The filename `-` is interpreted as standard input by many commands.

Use:

```bash
cat ./-
```

to explicitly reference the file.

---

#### Level 2 — Filenames with Spaces

Files containing spaces must either be quoted:

```bash
cat "filename with spaces"
```

or escaped:

```bash
cat filename\ with\ spaces
```

Using **Tab Completion** is faster and avoids typing mistakes.

---

#### Level 3 — Hidden Files

Files beginning with `.` are hidden by default.

Display them using:

```bash
ls -la
```

---

### 🖥️ Computer Fundamentals

Learned the roles of:

* CPU
* RAM
* Storage

TryHackMe explained them using parts of the human body, making the concepts easier to remember.

---

### 🔄 Boot Process

Current understanding:

```
Power On
    ↓
Firmware (BIOS / UEFI)
    ↓
Bootloader
    ↓
Operating System
```

This topic still needs additional review.

---

## ⚠️ Biggest Challenges

* Spent longer than expected solving Bandit Levels 1 and 2.
* Didn't fully understand the boot process.

---

## ✔️ Solutions

### Bandit Level 1

```bash
cat ./-
```

---

### Bandit Level 2

Used **Tab Completion** to automatically escape spaces.

---

### Boot Process

Marked for review instead of pretending I understood it.

---

## 💻 Commands Used

```bash
cat
ls
ls -la
./
Tab Completion
```

---

## 💭 Reflection

Today's challenges required more problem-solving than Day 1.

Instead of rushing through the material, I documented what I still don't understand. That feels like better progress than simply checking off completed rooms.

---

## 🚀 Tomorrow

* [ ] Complete Bandit Levels 4–6
* [ ] Finish the "Computer Types" room
* [ ] Revisit the boot process until it makes sense


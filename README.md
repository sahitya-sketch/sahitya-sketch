## Hi there 👋

<!--
**sahitya-sketch/sahitya-sketch** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

 # 🔐 Cybersecurity Admissions Portfolio | IIT Kanpur B.Cyber (2026)
### Applicant Identity & Screening Credentials
* **Candidate Name:** [Sahitya Jain]
* **JEE Main 2025/2026 Application Number:** [260310042766]
* **JEE Main Best Session Score:** [98.6728738]
* **Submission Date:** June 2026

---

## 🎯 Executive Summary
I am a dedicated student applying for the foundational **Bachelor of Cybersecurity (B.Cyber.) at IIT Kanpur**. Recognizing my baseline of zero structured computer science exposure, I built this portfolio via aggressive self-guided studies over several weeks. Rather than waiting for a university lecture, I have mapped out core concepts, initiated local defensive configurations, and solved standardized gamified security modules to validate my technical aptitude and problem-solving tenacity.

---

## 📑 1. Core Technical Foundations (Self-Guided Curriculums)
To transition from non-technical to application-ready, I engineered a personal curriculum focusing on infrastructure fundamentals.

### A. Linux & System Internals
* **Core Competency:** Transitioned completely from a GUI interface to navigating headless operating systems using the terminal.
* **Commands Mastered:** File navigation (`cd`, `ls -la`, `pwd`), permission management (`chmod 700`, `chown`), and process manipulation (`ps aux`, `kill -9`, `systemctl`).
* **Environment Strategy:** Configured a native environment running specialized Debian distributions.

### B. Networking Fundamentals (OSI Reference Mapping)
* **Layer 7 (Application):** Deepened knowledge on protocol structures including DNS resolution workflows and plaintext vs. encrypted transfers (HTTP vs HTTPS).
* **Layer 4 (Transport):** Analyzed the stateful three-way handshake of Transmission Control Protocol (TCP) versus the connectionless structure of User Datagram Protocol (UDP).
* **Layer 3 (Network):** Studied IPv4 subnet structuring, Network Address Translation (NAT) gateways, and public vs. private IP routing.

---

## 📑 2. Active Lab Deployments & Tooling Practice
*Evidence of hands-on simulation frameworks built completely within a standard local computer.*

### Lab 1: Defensive Local Network Architecture (Virtualization)
* **Objective:** Establish an isolated sandboxed environment to research scanning methodologies without exposing real devices to structural risk.
* **Architecture Design:** Built using **Oracle VirtualBox**. Configured an internal, host-only local virtual bridge network structure separating host files from experimental VMs.
* **Machine Deployments:** 
  1. *Attacker System:* Native installation of **Kali Linux**, isolating modern script packages.
  2. *Auditing Target:* Deployment of **Metasploitable2** (a Linux engine intentionally misconfigured with open ports to act as a target).
* **Validation Evidence:** Executed active scanning through network mapping tools (`nmap -sV -O [Target_IP]`). Successfully logged open ports 21 (FTP), 22 (SSH), and 80 (HTTP) along with their corresponding software version numbers.

### Lab 2: Automated Crypto-Entropy Generation Script (Python Architecture)
* **Objective:** Eliminate human pattern reliance in credential generation through programmatic automation.
* **Script Logic Execution:** Developed a modular Python script utilizing the standard cryptographic module `secrets` (rather than standard pseudo-random `random` functions) to fetch true unpredictable system entropy from the OS kernel.
* **Core Code Architecture:**
```python
import secrets
import string

def generate_secure_credential(length=16):
    # Combine structural character libraries to maximize complexity
    alphabet = string.ascii_letters + string.digits + string.punctuation
    # Enforce non-repeating cryptographically secure array generations
    secure_string = ''.join(secrets.choice(alphabet) for _ in range(length))
    return secure_string

print("Generated Secure Target Key: ", generate_secure_credential(24))
```
* **Git Repository Verification:** Code safely pushed and version-tracked via active branching inside this GitHub profile environment.

---

## 📑 3. Standardized Gamified CTF Write-Ups
*Evidence of applied logical debugging through top-tier beginner-friendly security challenges.*

### Framework A: TryHackMe Module Attainment
* **Track Completed:** **Pre-Security** & **Introduction to Cyber Security** Learning Paths.
* **Acquired Capabilities:** Successfully resolved operational room puzzles focusing on content discovery, basic network traffic inspection, and defending Windows system registries.
* **Profile Verification:** [https://tryhackme.com/p/sahityajain406]

### Framework B: PicoCTF Challenge Breakdowns
*   **Challenge 1: General Skills (Warmup Engine)**
    * *Objective:* Convert raw mathematical bases under strict system configurations.
    * *Problem-Solving Approach:* Provided with a hexadecimal string value. Used terminal manipulation tools via piping echo structures directly into base conversion arguments (`echo 0x3D | xxd -r -p`) to extract flag hashes.
*   **Challenge 2: Cryptography Basics (Rotational Ciphers)**
    * *Objective:* Decode message patterns obfuscated by cyclic alphabet shift frequencies.
    * *Problem-Solving Approach:* Identified a standard Caesar/ROT13 string configuration. Constructed a micro-map dictionary to perform character tracking index offsets (+13 positions), successfully decoding the text parameter to yield the completion flag.

---

## 📑 4. Verification Portfolio Checklist
- [x] Verified JEE Main scorecard file ready for [IIT Kanpur Portal upload](https://pingala.iitk.ac.in/CYBER_UGADM/login).
- [x] This open-source GitHub repository made entirely public for evaluator review.
- [x] Virtual configuration blueprints and core scripts hosted locally.
- [x] Fully prepared to travel to Kanpur for the **On-Campus Admissions Hackathon** if selected.

---
### 🛠️ Sign-Off Note
*This repository represents real, verified efforts of a self-taught, zero-knowledge student building a pathway into modern defense engineering. I am ready to be tested under timed conditions on campus.*

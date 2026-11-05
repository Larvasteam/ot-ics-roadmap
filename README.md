# 🛡️ OT & ICS Cybersecurity Self-Study Roadmap

A structured, 12-month self-study plan for mastering Operational Technology (OT) and Industrial Control Systems (ICS) security—from IT networking foundations to hands-on PLCs and industrial protocol pentesting.

---

## 🕒 Daily Study Routine

| Time Block | Focus | Strategy |
| :--- | :--- | :--- |
| **07:30 – 10:30 (Morning)** | **Deep Learning & Lab Work** | 3× 50-minute focused sprints (10-min breaks). Learn concepts, write code, run labs. |
| **22:00 – 00:00 (Night)** | **Recalls, Quizzes & Logs** | Spaced repetition flashcards, self-testing, and committing progress to GitHub. |

### ☀️ Morning Block Breakdown (07:30 – 10:30)
- **07:30 – 08:20 (Sprint 1):** Theory & Core Concepts (Read specs, standards, Purdue Model, lectures).
- **08:20 – 08:30:** Break.
- **08:30 – 09:20 (Sprint 2):** Hands-on Execution & Lab Work (Wireshark `.pcap` analysis, OpenPLC ladder logic, Python scripts).
- **09:20 – 09:30:** Break.
- **09:30 – 10:30 (Sprint 3):** Lab Wrap-Up & Notes Drafting (Save configurations, draft documentation).

### 🌙 Night Block Breakdown (22:00 – 00:00)
- **22:00 – 23:00:** Active Recall & Flashcards (Anki cards for ports, protocol function codes, syntax).
- **23:00 – 23:45:** Practice Quizzes & Scenario Testing (CISA modules, CTF challenges, self-quizzing).
- **23:45 – 00:00:** Git Commit & Check-Off (Update task list, push code and notes).

---

## 🗺️ Learning Roadmap & Progress Tracker

### 🔹 Phase 1: Core Networking & IT Security Foundations (Months 1–3)
- [ ] **Networking Fundamentals:** TCP/IP model, OSI layers, subnets, VLANs, and routing.
- [ ] **Wireshark Mastery:** Packet captures, packet inspection, display filters, and stream reassembly.
- [ ] **Linux & Scripting:** Bash navigation, Python fundamentals (sockets, Scapy basic packet generation).
- [ ] **Core Security Concepts:** CIA triad, firewalls, network segmentation, and basic vulnerability scanning.

### 🔹 Phase 2: OT Architecture, Frameworks & Industrial Protocols (Months 4–6)
- [ ] **Purdue Model:** Level 0 (Process) through Level 5 (Enterprise IT Network).
- [ ] **OT Standards & Frameworks:** ISA/IEC 62443, NIST SP 800-82, and MITRE ATT&CK for ICS.
- [ ] **Industrial Protocols (Deep Dive):**
  - [ ] Modbus TCP (Function codes, coils, registers)
  - [ ] DNP3 & OPC UA
  - [ ] EtherNet/IP & Profinet
- [ ] **Case Study Analysis:** Detailed notes on Stuxnet, Industroyer (Crashoverride), and Triton/TriSys.

### 🔹 Phase 3: Hands-on Simulation & Virtual Lab Setup (Months 7–12)
- [ ] **PLC Simulation:**
  - [ ] Install **OpenPLC Editor** & **OpenPLC Runtime** (Docker/VM).
  - [ ] Write basic ladder logic (start/stop latching circuit, timers).
- [ ] **Network Mapping & Monitoring:**
  - [ ] Run **GrassMarlin** to map virtual OT network topologies.
  - [ ] Set up **ScadaBR** / **ControlThing Suite** for HMI simulation.
- [ ] **Protocol Traffic Analysis:**
  - [ ] Capture live Modbus TCP read/write requests using Wireshark.
  - [ ] Write basic **Zeek** or **Snort/YARA** rules to detect unauthorized Modbus commands.

### 🔹 Phase 4: Professional Certifications & Specialization (Year 1+)
- [ ] **Foundational Certifications:** ISA/IEC 62443 Cybersecurity Fundamentals or CompTIA Security+.
- [ ] **Target OT Certifications:** Prepare for GICSP (Global Industrial Cyber Security Professional).
- [ ] **Advanced Specialization:** Explore Threat Hunting (GRID) or OT Pentesting/Red Teaming.

---

## 📁 Repository Directory Structure

```text
ot-ics-roadmap/
│
├── README.md                 <- Progress tracker and main roadmap
├── 01-foundations/           <- Wireshark cheat sheets, Python scripts, networking notes
├── 02-ot-architecture/       <- Purdue Model notes, protocol analysis, ICS attack write-ups
├── 03-hands-on-labs/         <- OpenPLC programs, Docker files, .pcap sample files
└── 04-certifications/        <- GICSP study guides, ISA/IEC 62443 notes, practice questions

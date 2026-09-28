# Week 3 - Password Cracking

**Intern:** Nur Izzati  
**Batch:** B083  
**Week:** 3  
**Project:** W3-PM1, W3-PM2, W3-OPTIONAL1 - Password Cracking  
**Date:** September 2026

---

## Project Overview

Week 3 focused on **password cracking techniques** using John the Ripper (JtR), NW Tools, and AI-assisted security tools. The activities covered password hash extraction, dictionary attacks, password recovery, and the use of Claude Desktop with Hexstrike MCP v1.

Three modules were completed:

- **W3-PM1** — Password Cracking with John the Ripper (JtR)
- **W3-PM2** — Password Cracking with NW Tools
- **W3-OPTIONAL1** — AI-Assisted JtR Password Cracking with Claude Desktop & Hexstrike MCP v1

All activities were performed using the files and environment provided for the authorized NetworkWalks Cybersecurity Internship.

---

## Tools Used

| Tool | Purpose | Platform |
|------|---------|----------|
| John the Ripper (JtR) | Password hash cracking | Kali Linux |
| NW Tools | Dictionary-based password cracking | Kali Linux |
| Claude Desktop | AI-assisted security tool interaction | Kali Linux |
| Hexstrike MCP v1 | MCP server for security tool integration | Kali Linux |
| MCP Server | Connects Claude Desktop with security tools | Kali Linux |
| Kali Linux | Password cracking environment | Virtual Machine |

---

# W3-PM1 - Password Cracking with John the Ripper

This module focused on using **John the Ripper (JtR)** to recover the password of a provided protected file.

## Methodology

### 1. Install and Set Up John the Ripper

Installed and configured John the Ripper in Kali Linux to prepare the environment for password cracking.

![Install John the Ripper](screenshots/install_jtr.png)

---

### 2. Extract the Password Hash

Extracted the password hash from the provided protected file so that it could be processed by John the Ripper.

![Extract password hash](screenshots/extract_hash.png)

---

### 3. Load the Hash and Perform Password Cracking

Loaded the extracted hash into John the Ripper and performed the password-cracking process to recover the password.

![Crack password with John the Ripper](screenshots/crack_pw.png)

---

### 4. Unlock the Protected File

Used the recovered password to unlock the protected file and verify that the password was successfully recovered.

![Unlock protected PDF](screenshots/unlock_pdf1.png)

---

## Outcome

Successfully recovered the password using John the Ripper and unlocked the first provided protected file.

---

# W3-PM2 - Password Cracking with NW Tools

This module focused on using **NW Tools** to recover the password of a second protected PDF through a dictionary attack.

## Methodology

### 1. Load the Protected PDF and Obtain the Hash

Loaded the second protected PDF and obtained the password hash required for the cracking process.

![Obtain PDF hash](screenshots/hash_pdf2.png)

---

### 2. Perform a Dictionary Attack

Used NW Tools to perform a dictionary attack against the extracted PDF password hash.

![Crack password with NW Tools](screenshots/crack_pw2.png)

---

### 3. Unlock the Protected PDF

Used the recovered password to unlock the second protected PDF.

![Unlock second PDF](screenshots/unlock_Pdf2.png)

---

## Outcome

Successfully performed a dictionary attack using NW Tools, recovered the password, and unlocked the second protected PDF.

---

# W3-OPTIONAL1 - AI-Assisted JtR Password Cracking with Claude & Hexstrike MCP v1

This optional module explored the use of **AI-assisted cybersecurity tools** by connecting Claude Desktop to the Hexstrike MCP v1 server in Kali Linux.

The exercise demonstrated how Claude Desktop can interact with security tools through the **Model Context Protocol (MCP)**.

## Methodology

### 1. Set Up Claude Desktop and the MCP Server

Configured Claude Desktop and the Hexstrike MCP server in Kali Linux to prepare the AI-assisted password-cracking environment.

![Set up MCP server](screenshots/setup_mcpserver.png)

---

### 2. Configure the Client-Server Connection

Edited the Claude Desktop configuration file to connect the Claude client with the Hexstrike MCP server.

![Edit Claude Desktop configuration](screenshots/edit_config.png)

---

### 3. Check the MCP Server Health

Checked the MCP server health to verify that the server was running correctly and that the connection was working.

![Check server health](screenshots/server_health.png)

---

### 4. Perform AI-Assisted Password Cracking

Used Claude Desktop to issue the password-cracking command through the connected MCP security tools and recover the password of the third provided file.

![Unlock third protected PDF](screenshots/unlock_pdf3.png)

---

## Outcome

Successfully configured Claude Desktop with Hexstrike MCP v1, verified the MCP server connection, and used the AI-assisted workflow to recover the password and unlock the third protected file.

---

# Project Comparison

| Module | Tool | Method | Outcome |
|------|------|--------|---------|
| W3-PM1 | John the Ripper | Hash extraction and password cracking | First file unlocked |
| W3-PM2 | NW Tools | Dictionary attack | Second PDF unlocked |
| W3-OPTIONAL1 | Claude Desktop + Hexstrike MCP + JtR | AI-assisted password cracking | Third PDF unlocked |

---

# Key Learnings

- Learned how password hashes can be extracted from protected files for offline password testing.
- Gained practical experience setting up and using John the Ripper in Kali Linux.
- Practiced dictionary-based password cracking using JtR and NW Tools.
- Learned how password recovery can be used to unlock protected files.
- Learned how to configure Claude Desktop with an MCP server.
- Gained experience checking MCP server health and client-server connectivity.
- Explored how AI can interact with cybersecurity tools through the Model Context Protocol.
- Understood the importance of performing password-cracking activities only within an authorized environment.

---

# Security & Ethical Use

All activities were performed strictly within the authorized scope of the NetworkWalks Cybersecurity Internship (Batch B083), using the files provided for the practical exercises.

No unauthorized password cracking, exploitation, or access to third-party systems was attempted.

---

# Conclusion

Week 3 covered practical password-cracking techniques using **John the Ripper, NW Tools, and AI-assisted security tools**.

The exercises covered password hash extraction, dictionary attacks, password recovery, and unlocking protected files. The optional module extended the practical work by connecting Claude Desktop with Hexstrike MCP v1 and using an AI-assisted workflow for password cracking.

These activities provided practical experience in password security, offline password testing, dictionary attacks, and the integration of AI with cybersecurity tools.

**Key lesson:** Strong and unique passwords are important because weak passwords can be vulnerable to dictionary-based and automated password-cracking techniques.

---

# Tags

`#NetworkWalks` `#Cybersecurity` `#KaliLinux` `#JohnTheRipper` `#PasswordCracking` `#DictionaryAttack` `#ClaudeDesktop` `#HexstrikeMCP` `#MCP` `#AIinCybersecurity` `#EthicalHacking` `#BatchB083`

<!-- hide -->
# 🔐 Cybersecurity Final Project

> Final project for the Cybersecurity Bootcamp at [4Geeks Academy](https://4geeksacademy.com). A complete hands-on exercise simulating a real-world security incident: forensic analysis, penetration testing, vulnerability remediation, and incident response planning on a compromised Debian server.

*Esta documentación también está [disponible en español](README.es.md)*

---

## 📌 Project Overview

This project simulates the role of a cybersecurity analyst tasked with recovering and securing a critical server that has been compromised. The exercise is divided into three phases covering the full incident response lifecycle.

---

## 🗂️ Deliverables

| File | Description |
|------|-------------|
| `informe_pentesting_MRMF.pdf` | Penetration testing report |
| `informe_incidente_ciberseguridad_MRMF.pdf` | Security incident report |
| `plan_recuperacion_MRMF.pdf` | Recovery and continuity plan |
| `presentacion_análisis_cibersec_MRMF.pdf` | Executive presentation (PDF) |
| `presentacion_análisis_cibersec_MRMF.pptx` | Executive presentation (PPTX) |
| `diagrama_red_proyecto_final_mockup.pkt` | Network diagram (Cisco Packet Tracer) |
| `VM_REMEDIADA.md` | Remediated VM documentation |

---

## 🔍 Phase 1 – Forensic Analysis & Hack Remediation

**Objective:** Identify how the server was compromised, block the exploit, and restore security.

- Reviewed system logs (`/var/log/auth.log`) to trace attacker access
- Identified suspicious processes, unauthorized users, and backdoors
- Performed rootkit and malware scanning
- Stopped compromised services and reverted attacker changes
- Hardened firewall rules, updated packages, and rotated credentials

📄 **Report:** `informe_incidente_ciberseguridad_MRMF.pdf`

---

## 🕵️ Phase 2 – Vulnerability Detection & Penetration Testing

**Objective:** Find and exploit a second vulnerability, document the process, and apply fixes.

- Full system scan using `Nmap` and related tools
- Detected and exploited a misconfiguration unrelated to the original hack
- Documented the exploitation chain and privilege escalation steps
- Applied remediation: closed ports, restricted access, corrected service configurations

📄 **Report:** `informe_pentesting_MRMF.pdf`

---

## 📋 Phase 3 – Incident Response Plan & ISO 27001 ISMS

**Objective:** Design a formal incident response plan and an Information Security Management System.

- Developed response plan following **NIST SP 800-61** guidelines (Identify → Contain → Eradicate → Recover)
- Defined DLP policies and data protection mechanisms (backups, encryption, access controls)
- Built an **ISMS aligned with ISO 27001**: risk analysis, security policies, and action plans

📄 **Reports:** `plan_recuperacion_MRMF.pdf` · `presentacion_análisis_cibersec_MRMF.pdf`

---

## 🗺️ Network Diagram

Network topology designed with **Cisco Packet Tracer**, reflecting the current infrastructure and recommended security changes.

📁 `diagrama_red_proyecto_final_mockup.pkt`

---

## 🛠️ Tools & Technologies

`Debian Linux` · `Nmap` · `SSH` · `MySQL` · `Apache` · `FTP` · `Packet Tracer` · `NIST SP 800-61` · `ISO 27001`

---

## 👤 Author

**Addraed**
Cybersecurity Bootcamp · 4Geeks Academy

---

## 📄 License

This project was completed as part of a structured bootcamp exercise originally created by [@rosinni](https://github.com/rosinni) and contributors at [4Geeks Academy](https://4geeksacademy.com). Content and reports authored by Addraed are shared for educational purposes.
<!-- endhide -->

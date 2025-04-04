# 🛡️ Final Cybersecurity Project: Malicious Activity Modeling with Soltra Edge (STIX/TAXII)

This repository documents my final project for Foundations of Cybersecurity, where I used Soltra Edge—a STIX/TAXII server—to model a specific real-world cyber threat. The objective was to research a malicious incident, break it down using STIX 1.x objects, and build out relationships using the Soltra Edge GUI.

---

## 📚 Overview

Throughout the course, we explored:
- What **Cyber Security Information** is and how it's structured
- The **Cyber Kill Chain**
- A case study involving **Trudy** and her malicious activities
- The role of **STIX/TAXII** in structuring and exchanging threat intelligence

For this final assignment, I applied those concepts to research, model, and visualize a malicious event using **Soltra Edge**.

---

## 🧠 Project Steps

### ✅ 1. Malicious Activity Selection
I selected a specific incident of malicious activity based on public APT reports. This attack was chosen based on the availability of sufficient threat intelligence data to fully model it using STIX objects.

### ✅ 2. Threat Modeling with STIX Objects
Using Soltra Edge's Web GUI, I modeled:
- **Incident(s)**
- **Actor(s)**
- **Campaign(s)**
- **TTP (Tactics, Techniques, and Procedures)**
- **Exploit Targets**
- **Indicators & Observables**
- **Course of Action (COA)**

All objects were connected with appropriate relationships to form a complete threat model.

### ✅ 3. Visualization with STIXviz
After completing the model in Soltra Edge, I exported the XML data and visualized it using [STIXviz](https://github.com/oasis-open/cti-stix-visualization).

---

## 🔧 Tools Used

| Tool | Purpose |
|------|---------|
| **Soltra Edge** | STIX/TAXII object creation & management |
| **VMware Workstation/Player** | Hosting the Soltra Edge OVA |
| **Firefox** | Browser recommended for Soltra Edge |
| **STIXviz** | Visualizing the STIX relationships |
| **MD5/SHA1 Checksum Tool** | Verifying the integrity of the image file |

---

## 🖥️ Soltra Edge Setup Notes

- **Login credentials**:  
  Username: `admin`  
  Password: `FC2stixtaxii`

- **Common Issues**:
  - GUI may load slowly—allocate more VM memory
  - Dashboard may freeze—navigate away from it quickly
  - If login fails repeatedly, redeploy the image
  - SSH is **disabled**; use the **Web GUI only**

---

## 📝 Final Report

The final report includes:
- A narrative description of the attack
- Documentation of all STIX objects used
- Explanation of object relationships
- Screenshots from Soltra Edge and STIXviz
- Citations for all researched threat intel

---


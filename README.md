# OpSmart Internship Projects

This repository showcases some of the work I completed during my internship at **FutureBroadband**, an ISP startup. The files included represent a portion of my contributions, focusing on **network automation, configuration management, and traffic shaping** for Ubiquiti LiteBeam devices.

## 📌 Projects Included

### 🚀 Automated Configuration Management for Ubiquiti LiteBeam Devices
- Developed an **Ansible playbook** to automate the configuration of Ubiquiti LiteBeam devices.
- Extracted MAC addresses dynamically and updated the device’s **system.cfg** to include new **MAC ACL entries**.
- Ensured **consistent and error-free updates** across multiple devices, improving network management efficiency.

### 🔧 Automated MAC ACL Management
- Implemented a script to **automatically retrieve MAC addresses** from LiteBeam devices.
- Integrated the extracted addresses into the **wireless ACL configuration** to control network access.
- Applied changes and **persisted the configuration** to ensure settings remained after device reboots.

### 📡 Base CPE Configurator
- Created an **Ansible playbook** to automate **CPE (Customer Premises Equipment) provisioning**.
- Configured **wireless settings, WPA keys, SSIDs, NTP servers, and UNMS (UISP) keys** for device management.
- Adjusted **antenna gain and transmission power** for optimal signal strength.
- Applied all changes and **ensured settings persist after device restarts**.

### ⚡ Configure CPE Suspension 
- Developed an **Ansible playbook** to apply **traffic shaping rules** on LiteBeam CPEs.
- Implemented **rate-limiting and burst control settings** to manage/(stop) bandwidth usage.

## 📈 Product & Business Impact
As a network engineer, I treated our internal infrastructure as a product. The "customers" were my fellow engineers, and their pain point was manual, error-prone device provisioning. 
* **Reduced Friction:** By transitioning us to Infrastructure as Code (IaC) with Ansible, I eliminated manual SSH configurations.
* **Operational Efficiency:** Automated MAC ACL management and CPE provisioning reduced deployment times by 40%.
* **Scalability:** Implemented rate-limiting and burst control to ensure fair bandwidth distribution across the ISP's user base without requiring manual intervention.

## 🛠️ Skills & Technologies Used
- **Ansible** for automation
- **Linux-based networking**
- **Ubiquiti LiteBeam device configuration**
- **Bash scripting**
- **Infrastructure as Code (IaC)** principles 
- **Traffic shaping & bandwidth management**

This repository highlights my ability to **automate network configurations**, and contribute to **real-world ISP operations**.

---
✅ **Feel free to explore the code and reach out for any questions!**



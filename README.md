# 🔐 Windows Security Hardening Lab

## 📌 Overview
This project demonstrates core security hardening techniques performed on a Windows 11 system.  
The goal is to reduce attack surface, increase protection against ransomware, and follow best practices used in modern IT support and cybersecurity.

---

## 🛠️ Hardening Tasks Completed

### ✔️ 1. Enabled Windows Defender Firewall (All Profiles)
Firewall ensures unauthorized incoming/outgoing traffic is blocked unless explicitly allowed.

📸 **Screenshot:**  
`/screenshots/firewall_home.png`

---

### ✔️ 2. Created a Custom Firewall Rule
I created a custom outbound rule named **my_super_cool_rule** using Windows Defender Firewall with Advanced Security.

📸 **Screenshot:**  
`/screenshots/firewall_rule.png`

**Why This Matters:**  
Custom rules control how specific applications communicate with the network, reducing risk from unauthorized apps or malware.

---

### ✔️ 3. Verified Windows Defender Antivirus Configuration
Real-time protection, cloud-delivered protection, and automatic sample submission were verified as enabled.

📸 **Screenshot:**  
`/screenshots/defender_overview.png`

**Why This Matters:**  
Ensures malware is detected and blocked in real time.

---

### ✔️ 4. Enabled Ransomware Protection (Controlled Folder Access)
Turned on Controlled Folder Access to protect Documents, Desktop, Pictures, and other personal folders from unauthorized changes.

📸 **Screenshot:**  
`/screenshots/ransomware_protection.png`

**Why This Matters:**  
Prevents ransomware from encrypting or deleting important data.

---

### ✔️ 5. Disabled Unnecessary Startup Apps
Reviewed and disabled unnecessary applications that start up with Windows to improve performance and reduce background vulnerabilities.

📸 **Screenshot:**  
`/screenshots/startup_apps.png`

**Why This Matters:**  
Fewer startup apps = faster boot times and fewer vectors for malware or unwanted services.

---

## 📝 Summary of Improvements

| Category | Before | After |
|----------|--------|-------|
| Firewall | Enabled, default rules | Custom rules + review of allowed apps |
| Antivirus | Running | Verified settings + fully enabled protection |
| Ransomware Protection | Off | **ON** with protected folders |
| Startup Apps | Many enabled | Only essential apps enabled |
| System Hardening | Basic | Hardened using best practices |

---

## 🧠 Lessons Learned

- How Windows Firewall filters incoming and outgoing network traffic  
- How custom firewall rules can restrict or allow specific applications  
- How Controlled Folder Access blocks ransomware attempts  
- The importance of real-time antivirus protection  
- How reducing startup apps improves security and performance  

---

## 📚 Tools Used
- Windows Security  
- Windows Defender Firewall (Advanced Settings)  
- Task Manager  
- Local System Settings  

---

## ✅ Status
✔️ Completed and documented  
✔️ Screenshots included  
✔️ Ready for recruiters and portfolio reviews  

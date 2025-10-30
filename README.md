  # 👋 Hi, I'm Shabbir
 ### 🧑‍💻 IT Engineer | Transitioning from IT Engineering → Cloud/DevOps.

## 🧑‍💻 About Me
- 💡 Transitioning from IT Engineering → Cloud/DevOps
- 💬 Ask me about: Systems Administration, Cloud Services, Automation & CICD.
- 📫 Connect: [LinkedIn](https://linkedin.com/in/yourprofile)

  
## 🔧 Tools & Technologies
Networking | Linux | AWS | Shell Scripting| Terraform | Git | Docker | Kubernetes | Jenkins | Ansibile

This portfolio highlights my Cloud/DevOps learning projects and hands-on automation Task.

## 📂Cloud/DevOps Projects

 | Project                                   | Description                                                      |
| ----------------------------------------- | ---------------------------------------------------------------- |
| **Project 1:** User Management            | Automate user creation and permission setup via bash script      |
| **Project 2:** Apache/Nginx Web Server    | Install, configure, and host a static website                    |
| **Project 3:** Secure MySQL Database      | Install & secure MySQL (disable remote root, set password, etc.) |
| **Project 4:** Shell Scripting Automation | Write a script for backup, logs rotation, or user reporting      |
| **Project 5:** Setup YUM / APT Local Repo | Host your own repository server                                  |
| **Project 6:** System Monitoring          | Use `crontab` + `sar` or `vmstat` to schedule monitoring logs    |
| **Project 7:** Firewall & SELinux Config  | Configure `firewalld` and manage SELinux policies                |


## 🚀 Beginner DevOps & Linux Projects

> 💡 *Hands-on projects to build my foundation in Databases, Web Servers, File Servers, and Bash Automation.*

---

### 🗄️ **Database Projects**
| 🔢 **Project** | 🧠 **Description** |
|----------------|------------------|
| **MySQL / MariaDB Setup** | 🛠️ Install & configure MySQL or MariaDB, create a sample database, manage users, and secure it (disable remote root access, strong passwords). |
| **PostgreSQL Configuration** | 🧩 Install PostgreSQL, create a database, enable secure remote access, and automate regular backups using Bash. |

---

### 🌐 **Web Server Projects**
| 🌍 **Project** | 🧠 **Description** |
|----------------|------------------|
| **Apache / Nginx Web Hosting** | ⚙️ Install and configure Apache or Nginx to host a static or dynamic site (e.g., WordPress using MySQL backend). |
| **Virtual Host & SSL Setup** | 🔒 Configure multiple virtual hosts and enable HTTPS using free SSL certificates (Let's Encrypt). |

---

### 📂 **File Server Projects**
| 🗃️ **Project** | 🧠 **Description** |
|----------------|------------------|
| **NFS Server Configuration** | 📡 Set up an NFS server to share directories between Linux systems. Configure proper access control and persistent mounts. |
| **Samba File Sharing** | 💾 Install and configure Samba for cross-platform (Linux ↔ Windows) file sharing. Manage user authentication and access permissions. |

---

### ⚙️ **Bash Scripting & Automation**
| 🖥️ **Project** | 🧠 **Description** |
|----------------|------------------|
| **User Management Automation** | 👥 Write a Bash script to automate user creation, permission setup, and password policies. |
| **System Resource Utilization Script** | 📊 Create a script to check CPU, memory, and disk usage. Schedule reports using `cron` for automation. |
| **Backup Automation Script** | 🗂️ Automate backup of critical config files or logs. Add compression, timestamps, and automatic cleanup. |

---

### 🧰 **Skills Covered**
`Linux Administration` • `MySQL / MariaDB / PostgreSQL` • `Apache / Nginx` • `NFS / Samba` • `Bash Scripting` • `Automation` • `System Security`

---
⭐*These projects are great starting points to building my  DevOps fundamentals in Linux, databases, web hosting, and scripting automation.*

# 🚀 Install and Secure MariaDB on AWS EC2

## 📘 Project Overview
This project demonstrates how to **install, configure, and secure MariaDB** on an **AWS EC2 instance**.  
It’s part of my DevOps & Linux Administration learning journey to showcase hands-on database setup for a production-like environment.

---

## 🧩 Objective
- Deploy MariaDB on an AWS EC2 instance  
- Secure the installation  
- Create a database and user  
- (Optional) Enable remote access  
- Prepare a portfolio-ready documentation  

---

## ☁️ AWS Setup

### Step 1: Launch EC2 Instance
- **AMI:** Amazon Linux 2023 / CentOS / RHEL  
- **Instance Type:** t2.micro (Free Tier)  
- **Security Group:**  
  - Allow **SSH (22)** from your IP  
  - Allow **MySQL/MariaDB (3306)** from your IP if remote access needed  
- **Key Pair:** Create or use existing  

---

## 🔗 Step 2: Connect to EC2
```bash
ssh -i "your-key.pem" ec2-user@<your-ec2-public-ip>


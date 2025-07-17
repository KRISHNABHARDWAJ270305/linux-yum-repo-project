===============================================================================================================
# Offline YUM Repository Setup in RHEL 9

## 📌 Project Overview
This project demonstrates how to set up an **offline YUM repository** using RHEL 9 BaseOS and AppStream ISO files.  
It simulates real-world Linux server management where internet access is limited.

## ⚙️ Tools & Platform Used
- RHEL 9 (in VMware Workstation)
- Terminal (root user access)
- ISO image of RHEL 9

## 🧩 Steps Performed

1. **Mount the RHEL ISO:**
   Mounted BaseOS & AppStream ISO to `/mnt`.

2. **Created local repo file:**
   Added `.repo` files under `/etc/yum.repos.d/` with proper baseurl.

3. **Cleaned existing metadata:**
yum clean all

4. **Verified repository:**
   
5. **Installed test packages (e.g., tree):**
Verified that packages install via the offline YUM repository.

## 📷 Screenshots
All key steps are available in the uploaded screenshots:
- step1.jpg to step5.jpg

## 🧠 What I Learned
- How to configure repositories in Linux manually
- Working with `.repo` files and ISO mounting
- Basics of package management without internet
===============================================================================

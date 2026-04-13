## ⚙️ User Data Script

This script is used in the Launch Template to automatically configure EC2 instances created by the Auto Scaling Group.

---

### 📌 What the Script Does

* Updates the system packages
* Installs Apache web server (httpd)
* Starts and enables Apache service
* Creates a dynamic web page

---

### 📌 Dynamic Data Displayed

The script fetches instance metadata and displays:

* Instance ID
* Availability Zone
* Hostname

---

### 💡 Why This is Important

* Auto Scaling creates instances automatically
* Manual configuration is not possible
* User Data ensures every instance is identically configured

---

### 🔥 Key Insight

> Every EC2 instance launched by the Auto Scaling Group becomes a fully configured web server without manual intervention.

---

### 🎯 Interview Insight

> “User data scripts are used in Launch Templates to automate EC2 configuration, ensuring consistency and enabling fully automated infrastructure.”

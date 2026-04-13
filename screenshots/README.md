## 📸 Screenshots

This folder contains screenshots demonstrating the complete setup and working of the Auto Scaling system with Application Load Balancer.

---

### 📌 Screenshot Explanation

* **01-launch-template.png**
  Shows the configuration of the Launch Template used by Auto Scaling Group

* **02-user-data.png**
  Displays the user data script used for automatic EC2 setup

* **03-asg-config.png**
  Shows Auto Scaling Group configuration (min, desired, max capacity)

* **04-asg-activity.png**
  Demonstrates instance replacement and scaling activity

* **05-ec2-instances.png**
  Shows EC2 instances launched by Auto Scaling

* **06-alb-active.png**
  Displays Application Load Balancer in active state

* **07-target-group-healthy.png**
  Shows target group with healthy instances

* **08-alb-output1.png & 08-alb-output2.png**
  Demonstrates load balancing across multiple EC2 instances

* **08-apache-webpage-output.png**
  Shows web application response served from EC2

---

### 💡 What This Proves

* Auto Scaling automatically launches and replaces EC2 instances
* Application Load Balancer distributes traffic across instances
* Health checks ensure only healthy instances receive traffic
* System achieves high availability and fault tolerance

---

### 🔥 Interview Insight

> “The screenshots confirm that traffic is routed through ALB and Auto Scaling ensures continuous availability by replacing unhealthy instances.”

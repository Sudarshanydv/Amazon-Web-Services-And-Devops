# 🌥️ AWS CloudWatch

## 📌 What is AWS CloudWatch?

CloudWatch is a **monitoring and observability service** in AWS.  
It collects **metrics, logs, and events** from AWS resources and applications so you can:

- ✔ Monitor performance
- ✔ Detect issues faster
- ✔ Automatically take actions when something goes wrong
- ✔ Improve operational health and cost visibility

---

## 🎯 Why do we use CloudWatch?

In Cloud/DevOps, we must always monitor resources like **EC2, RDS, Lambda, VPC** etc.

CloudWatch helps you:

- 🔹 Check CPU / Memory / Network usage
- 🔹 Monitor application logs
- 🔹 Set alarms when something is wrong
- 🔹 Automatically stop, start, or scale resources
- 🔹 Trace real-time performance

---

## ⚙️ CloudWatch Key Features

| Feature | Explanation | Example Use Case |
|--------|-------------|----------------|
| **Metrics** | Collects performance data of AWS resources | CPU Utilization of EC2, RDS DB connections |
| **Logs** | Store and analyze application/system logs | Store EC2 logs for troubleshooting |
| **Alarms** | Trigger actions when metric crosses threshold | Auto-restart EC2 if CPU > 90% |
| **Dashboards** | Visual monitoring in single panel | Custom dashboard for project |
| **Events / EventBridge** | Automate actions based on events | Start EC2 every morning 9 AM |
| **Insights** | SQL-based log analysis | Find errors in Lambda logs easily |
| **Synthetics & X-Ray** | App monitoring & tracing | Trace API latency and errors |
| **Anomaly Detection** | AI detects unusual behaviour | Detect sudden traffic spike |

---

## 🚀 How to Use CloudWatch

### ▶ Monitoring EC2 Example
1️⃣ Go to CloudWatch Console  
2️⃣ Open **Metrics → EC2**  
3️⃣ Select CPU Utilization or Network Traffic  
4️⃣ Create **Alarm**  
5️⃣ Set threshold (ex: CPU > 80%)  
6️⃣ Notify via **SNS** or take action (Auto scale / restart)  

---

### ▶ Monitoring Logs Example
1️⃣ Install **CloudWatch Agent** on EC2  
2️⃣ Create a **Log Group** (ex: `/app/logs`)  
3️⃣ Logs will appear inside CloudWatch Logs  
4️⃣ Search logs using **Insights**  

---

## 🧠 Benefits of CloudWatch

- ✔ Real-time monitoring
- ✔ Improves uptime & system health
- ✔ Cost optimization with usage visibility
- ✔ Fast troubleshooting using logs & alerts
- ✔ Central monitoring for all AWS services
- ✔ Automation using alarms + Lambda/EventBridge

---

## 🔚 Short Interview Summary

> **CloudWatch is a monitoring and alerting service in AWS that collects metrics, logs, and events to improve performance, reliability, and automation of cloud resources.**

---

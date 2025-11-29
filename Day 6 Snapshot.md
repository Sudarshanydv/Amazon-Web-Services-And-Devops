## Name – Sudarshan Yadav, Contact - 7709877817
## Email Id – sudarshanyadav4080@gmail.com

# AWS Snapshot

## AWS Snapshot — Simple Step-by-Step
What is a Snapshot?
A snapshot is a backup of your storage in AWS.
Mostly used for:
•	EBS Volume backup (EC2 disks)
•	RDS Database backup
•	Creating AMI for new servers
________________________________________
## 🔹 EBS Snapshot (EC2 Disk Backup)
Steps:
1️⃣ Select an EBS Volume
2️⃣ Click Create Snapshot
3️⃣ Snapshot gets stored in S3 (internally by AWS)
4️⃣ You can restore that snapshot to a new EBS Volume
5️⃣ Attach the volume to any EC2 instance and use it again
Simple example:
•	Before updating server → take snapshot
•	If update fails → restore snapshot → server comes back to old state
________________________________________
## 🔹 RDS Snapshot (Database Backup)
Steps:
1️⃣ Select RDS Database
2️⃣ Click Take Snapshot
3️⃣ AWS stores backup of the full DB
4️⃣ You can restore DB anytime from that snapshot
Used for:
•	Database backup
•	Database disaster recovery
________________________________________
🔹 Important Things to Remember
Feature	Meaning
Incremental	Only changed data stored → saves cost
Encrypted	Can protect data with KMS
Cross-Region Copy	Useful for disaster recovery
Manual Delete	Old snapshots cost money → delete when not needed
________________________________________
## 🔥 Simple One-Line Answer for Interview
“Snapshot is a point-in-time backup of AWS storage like EBS and RDS. We take snapshots before changes and restore them when needed for backup and disaster recovery.”
🔗 Connect With Me
GitHub: https://lnkd.in/d2F3JPa3
Dev.to Blog: https://lnkd.in/dNtgqAME
LinkedIn: https://lnkd.in/d3NctxFT
Resume (Google Drive): https://lnkd.in/dHDNsd_D

… Thank You …

# 🚀 Day 14 – AWS Cloud Security & Encryption

---

# 📌 Overview

On Day 14, I explored AWS Cloud Security concepts and encryption techniques used to protect cloud resources, applications, and sensitive data.

This day focused on:

* Cloud security fundamentals
* Encryption concepts
* IAM security
* AWS KMS
* Network security
* Monitoring & compliance

---

# ☁️ What is Cloud Security?

Cloud security refers to the protection of:

* Data
* Applications
* Infrastructure
* Networks
* User access

using security controls, encryption, monitoring, and policies.

---

# 🔐 Key Security Principles

## 1. Confidentiality

Protecting sensitive data from unauthorized access.

---

## 2. Integrity

Ensuring data is not modified improperly.

---

## 3. Availability

Making sure services are accessible when needed.

---

# 🔑 AWS Security Services

| Service         | Purpose                   |
| --------------- | ------------------------- |
| IAM             | Access management         |
| KMS             | Encryption key management |
| CloudTrail      | Logging & auditing        |
| GuardDuty       | Threat detection          |
| Security Groups | Firewall protection       |
| AWS Shield      | DDoS protection           |

---

# 🔒 What is Encryption?

Encryption converts readable data into unreadable ciphertext.

Only authorized users with the correct key can decrypt the data.

---

# 🧱 Types of Encryption

## 1. Encryption at Rest

Protects stored data.

### Examples:

* S3 bucket encryption
* EBS volume encryption
* DynamoDB encryption

---

## 2. Encryption in Transit

Protects data while transferring.

### Examples:

* HTTPS
* SSL/TLS

---

# ⚙️ AWS KMS (Key Management Service)

AWS KMS helps create and manage encryption keys securely.

### Features:

* Centralized key management
* Automatic rotation
* Access control using IAM
* Integration with AWS services

---

# 🌐 Real-World Project – Secure File Storage System

---

# 🏗️ Project Objective

Build a secure cloud storage architecture where:

* Users upload files securely
* S3 encrypts files automatically
* IAM controls access
* CloudTrail logs activity
* GuardDuty monitors threats

---

# 🧠 Project Architecture

```plaintext id="4vxw48"
User Upload
      ↓
Amazon S3
      ↓
KMS Encryption
      ↓
Secure Storage
      ↓
CloudTrail Logging
      ↓
GuardDuty Monitoring
```

---

# 🔐 Security Features Implemented

* IAM least privilege access
* S3 bucket encryption
* KMS-managed keys
* CloudTrail auditing
* HTTPS-only access
* MFA enabled accounts

---

# 📊 Monitoring & Compliance

## CloudTrail

Tracks:

* User activity
* API calls
* Access history

---

## GuardDuty

Detects:

* Suspicious activity
* Unauthorized access
* Threats & anomalies

---

# 🔟 Real-World Use Cases

1. Secure file storage
2. Banking applications
3. Healthcare systems
4. Government cloud platforms
5. AI/ML data protection
6. SaaS applications
7. Enterprise cloud security
8. Secure backups
9. Compliance management
10. Data protection systems

---

# 💻 Example Encryption Workflow

```plaintext id="pn3r0y"
User Data
    ↓
AWS KMS Encrypts Data
    ↓
Encrypted Data Stored in S3
    ↓
Authorized User Decrypts Data
```

---

# 🧪 Hands-On Tasks

## Task 1

Create encrypted S3 bucket.

---

## Task 2

Enable KMS encryption.

---

## Task 3

Configure IAM policies.

---

## Task 4

Enable CloudTrail logging.

---

## Task 5

Test secure file upload.

---

# 🧠 What I Learned

* Cloud security principles
* Encryption fundamentals
* AWS KMS architecture
* Secure AWS storage
* Monitoring & threat detection

---

# 🚀 Next Step (Day 15)

* AWS VPC Advanced Networking
* NAT Gateway & Route Tables

---

# 📌 Author

**Sankar S**
Cloud & AI Learning Journey 🚀

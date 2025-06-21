# aws-cli-project-2

# 🚀 Project 2: Command-Line Mastery with AWS CLI

This project is a part of my cloud learning journey and demonstrates AWS CLI usage to manage Amazon S3 buckets and objects. It simulates real-world cloud operations.

---

## 🧠 Objectives

- ✅ Install and configure the AWS Command Line Interface (CLI)
- ✅ Create and manage S3 buckets using AWS CLI
- ✅ Upload, list, and delete objects in S3

---

## 🔧 Tools & Technologies

- **AWS CLI v2**
- **Amazon S3**
- **IAM for Access/Secret Keys**
- **Windows PowerShell / Terminal**

---

### 📌 Installing and Configuring AWS CLI

Steps performed:
```bash
# Check AWS CLI version
aws --version

# Configure AWS credentials
aws configure
# Provided: Access Key ID, Secret Access Key, Region, Output format


### 📸 Screenshots of my project

aws s3 ls output


Confirmation of bucket creation

Upload success

---

### 🧰 Quick AWS CLI Reference

| Task               | Command                                              |
| ------------------ | ---------------------------------------------------- |
| Check AWS version  | `aws --version`                                      |
| Configure CLI      | `aws configure`                                      |
| List buckets       | `aws s3 ls`                                          |
| Create bucket      | `aws s3 mb s3://<bucket-name>`                       |
| Upload file/folder | `aws s3 cp <source> s3://<bucket-name>/ --recursive` |
| Delete file/folder | `aws s3 rm s3://<bucket-name>/<path> --recursive`    |
| Delete bucket      | `aws s3 rb s3://<bucket-name> --force`               |

---

✨ Key Takeaways
AWS CLI enables fast, repeatable cloud operations without GUI

IAM credentials are critical for access control and security

You can manage full lifecycle of S3 buckets from terminal


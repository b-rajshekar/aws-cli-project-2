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

- **Check AWS CLI version**
aws --version

- **Configure AWS credentials**
aws configure

- **Provided: Access Key ID, Secret Access Key, Region, Output format**

---


### 📸 Screenshots of my project

**✅ Checked the AWS CLI version:**

![Screenshot 2025-06-20 233458](https://github.com/user-attachments/assets/855fa9de-921b-47c9-b8b4-f82fa1847c79)


**✅ Verified AWS Identity using:**

![image](https://github.com/user-attachments/assets/21193d1d-e6f7-4eaf-a995-107362c937d5)


**✅ Created an S3 Bucket using AWS CLI**

![Screenshot 2025-06-21 055559](https://github.com/user-attachments/assets/1a0bafae-ff96-42d0-b754-aa0f1ae31bf5)
![Screenshot 2025-06-21 055608](https://github.com/user-attachments/assets/608ccda8-ff65-4b4e-b7e0-67e3eecd677b)


**📤 Uploaded Folder to S3 Bucket Using Environment Variable and Recursive Upload**

After creating the bucket, I uploaded a local folder (`beach-photos`) to a specific folder path in my S3 bucket. To make the command reusable, I set the bucket name as an environment variable.
![Screenshot 2025-06-21 062232](https://github.com/user-attachments/assets/1e24cd10-a105-437f-a298-9b63ada6204f)


**📁 Successfully Uploaded All Photos to S3 Using AWS CLI**

![Screenshot 2025-06-21 063129](https://github.com/user-attachments/assets/051d39a5-126f-4e41-99fe-1f277dc21f9b)

**📂 Verified Upload by Listing S3 Bucket Contents**

![Screenshot 2025-06-21 064532](https://github.com/user-attachments/assets/ec5749c2-7ce2-4075-8a20-7f2fec77af3e)

**🔍 Verified Uploaded Files Using Recursive List Command**

![Screenshot 2025-06-21 064717](https://github.com/user-attachments/assets/35b5942b-6ed2-4d52-8947-4ad89730aa57)

**🗑️ Deleted Files from S3 Bucket Using AWS CLI**

![Screenshot 2025-06-21 064831](https://github.com/user-attachments/assets/3f82bc69-34f4-48e3-a367-c8e4d9696935)
![Screenshot 2025-06-21 064939](https://github.com/user-attachments/assets/45dbcd11-7b1f-4cea-8f37-960834dd7aca)
![Screenshot 2025-06-21 064948](https://github.com/user-attachments/assets/d8f3a959-da96-4b59-a302-f59145e12a10)

**🗑️ Deleted the Entire S3 Bucket**

![Screenshot 2025-06-21 065026](https://github.com/user-attachments/assets/242e11ff-0148-48fc-aea9-258168918f46)
![Screenshot 2025-06-21 065038](https://github.com/user-attachments/assets/fa07ac93-b761-4cd5-b99e-7e2979a2fb0e)
![Screenshot 2025-06-21 065351](https://github.com/user-attachments/assets/53f6b580-0501-46a8-90ad-1311ea46e813)
![Screenshot 2025-06-21 065430](https://github.com/user-attachments/assets/6b997a69-c633-418e-9577-30425136dbf2)
















- aws s3 ls output
- Confirmation of bucket creation
- Upload success

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

- AWS CLI enables fast, repeatable cloud operations without GUI

- IAM credentials are critical for access control and security

- You can manage full lifecycle of S3 buckets from terminal


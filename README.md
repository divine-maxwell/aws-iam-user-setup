# 🧑‍💻 AWS IAM User Setup Project

## 📌 Project Overview
This project demonstrates how to provision IAM users in AWS, assign appropriate permissions, and test login functionality.  
It also validates **access boundaries** by confirming successful access to allowed resources (S3) and denial for unauthorized services (like CloudWatch Logs).

---

## 🛠️ What I Did
1. Created IAM users via the AWS Management Console.
2. Assigned managed and custom S3 policies for fine-grained access control.
3. Shared IAM sign-in URL and credentials with the test user.
4. Logged in as the IAM user to test:
   - ✅ Uploading and deleting S3 objects
   - ✅ Viewing bucket contents
   - ❌ Denied access to other AWS services like CloudWatch

---

## ✅ Test Results

| Action Tested             | Result   | Screenshot |
|---------------------------|----------|------------|
| IAM User Created          | ✅ Success | [📸 View](./screenshots/iam-users.png) |
| Login Link Access         | ✅ Success | [📸 View](./screenshots/login-link.png) |
| IAM User Login            | ✅ Success | [📸 View](./screenshots/user-login-success.png) |
| S3 Upload (PutObject 1)   | ✅ Success | [📸 View](./screenshots/s3-PutObject-upload01.png) |
| S3 Upload (PutObject 2)   | ✅ Success | [📸 View](./screenshots/s3-PutObject-upload02.png) |
| S3 Delete Object          | ✅ Success | [📸 View](./screenshots/s3-DeleteObj.png) |
| Permissions Attached      | ✅ Done    | [📸 View](./screenshots/permissions--attached.png) |
| Policy Reviewed           | ✅ Done    | [📸 View](./screenshots/permission-policy-reviewed.png) |
| S3 Access Test            | ✅ Success | [📸 View](./screenshots/access-test-success.png) |
| CloudWatch Logs Access    | ❌ Denied  | [📸 View](./screenshots/access-denied-cloudwatch.png) |

## 🖼️ Screenshot Previews

Below are clickable previews of key screenshots:

| Action | Preview |
|--------|---------|
| IAM User List | [<img src="./screenshots/iam-users.png" width="200"/>](./screenshots/iam-users.png) |
| Login Link Page | [<img src="./screenshots/login-link.png" width="200"/>](./screenshots/login-link.png) |
| User Login Success | [<img src="./screenshots/user-login-success.png" width="200"/>](./screenshots/user-login-success.png) |
| Upload to S3 #1 | [<img src="./screenshots/s3-PutObject-upload01.png" width="200"/>](./screenshots/s3-PutObject-upload01.png) |
| Upload to S3 #2 | [<img src="./screenshots/s3-PutObject-upload02.png" width="200"/>](./screenshots/s3-PutObject-upload02.png) |
| Delete S3 Object | [<img src="./screenshots/s3-DeleteObj.png" width="200"/>](./screenshots/s3-DeleteObj.png) |
| Access Denied (CloudWatch) | [<img src="./screenshots/access-denied-cloudwatch.png" width="200"/>](./screenshots/access-denied-cloudwatch.png) |

## 🧰 AWS Services Used

- **IAM** – Identity and Access Management
- **S3** – Simple Storage Service
- **CloudWatch** – (Used to test denied access)
- **AWS Console** – For provisioning and testing

---

## 🔐 Security Concepts Practiced

- IAM User Creation
- Access Key Management
- Identity-Based Access Control (IBAC)
- Testing Permission Boundaries
- Principle of Least Privilege
- AWS Sign-In URL usage

---

## 📁 Project Structure

aws-iam-user-setup/
├── README.md
└── screenshots/
├── iam-users.png
├── login-link.png
├── user-login-success.png
├── s3-PutObject-upload01.png
├── s3-PutObject-upload02.png
├── s3-DeleteObj.png
├── permissions--attached.png
├── permission-policy-reviewed.png
├── access-test-success.png
└── access-denied-cloudwatch.png

---

✅ **This project demonstrates hands-on AWS IAM provisioning and real-world access testing in a secure environment.**

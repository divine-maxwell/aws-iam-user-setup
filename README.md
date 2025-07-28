# AWS IAM User Creation & Login Validation

## 🔐 Project Description
This project demonstrates the setup of IAM (Identity and Access Management) users in AWS. I created a new user account, configured its sign-in permissions, and successfully tested login to verify proper account setup. This project is part of my hands-on beginner portfolio in Cloud Security.

## 📌 Project Goals
- Create an IAM user from the AWS console
- Retrieve account ID and sign-in URL
- Log in as the IAM user to verify permissions
- Understand IAM login workflows and user boundaries

## 🛠️ Tools Used
- AWS Management Console (IAM)
- GitHub (for portfolio tracking)
- macOS Terminal

## 📝 Steps Performed
1. Created an IAM user: `Tomiwa.Addict`
2. Enabled AWS Console access with a password
3. Retrieved the AWS Account ID from the admin console
4. Logged in using the IAM sign-in URL
5. Verified login was successful using the user’s credentials

## 📸 Screenshot
IAM login test from the user’s perspective:

![IAM Login](screenshots/iam-login-photo.jpg)

## 🔐 Security Notes
- Used a strong password format: `Uppercase + lowercase + numbers + symbol`
- IAM user was not granted administrator privileges
- Account alias and sign-in URL were customized for easier access

## 💡 What I Learned
- IAM user login doesn’t require a new AWS account
- AWS sign-in URLs can use either Account ID or Alias
- IAM policies and permissions shape what a user can do

## 📁 Project Structure

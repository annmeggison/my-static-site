  

---

## 🌐 Static Website Hosting on AWS S3 with GitHub Actions CI/CD

### 🔧 Project Overview

This project demonstrates how to host a static website using **Amazon S3** and automate deployments using **GitHub Actions**. Every time I push an update to my GitHub repository, the latest version of the website is automatically deployed to my S3 bucket — no manual uploading needed!

---

### 🧠 What I Learned

* How to set up and configure **S3 static website hosting**
* Creating and applying **bucket policies** for public access
* Managing **IAM users** securely for programmatic access
* Automating deployment with **GitHub Actions**
* Basic use of **AWS CLI** for syncing files

---

### 🚀 Tech Stack

* **AWS S3** – for static web hosting
* **GitHub Actions** – to automate deployment
* **HTML/CSS** – basic web content
* **IAM** – for secure access control
* **AWS CLI** – for command-line deployment

---

### 📁 Folder Structure

```
my-static-site/
├── index.html
└── .github/
    └── workflows/
        └── deploy.yml
```

---

### 🛠 How It Works

1. Simple static website built with HTML.
2. Hosted publicly on an **AWS S3 bucket** with public-read permissions.
3. CI/CD pipeline built using **GitHub Actions**.
4. On every push to the `main` branch:

   * GitHub Action runs
   * Files are synced to the S3 bucket using AWS CLI
   * Website is updated automatically

---

### 🔐 Security

* Used **GitHub Secrets** to store:

  * `AWS_ACCESS_KEY_ID`
  * `AWS_SECRET_ACCESS_KEY`
  * `AWS_REGION`
  * `S3_BUCKET_NAME`



---

### 📌 Live URL

> **Website URL**: [https://my-staticweb-site2.s3.amazonaws.com/index.html](#)
> (Replace this with your actual S3 endpoint or custom domain if used)

---

### 📷 Screenshot

> *<img width="1208" height="712" alt="image" src="https://github.com/user-attachments/assets/4a50ca57-7d69-4e8f-bac9-12b2a53e95d1" />
<img width="1007" height="480" alt="image" src="https://github.com/user-attachments/assets/8fff9a8e-f578-4187-800b-e15d42215f74" />
<img width="1002" height="396" alt="image" src="https://github.com/user-attachments/assets/1b5f4789-137b-4b19-b9b4-655ed0d5f97f" />


---

### 👩🏽‍💻 Author

**Anna Meggison**

* AWS Certified Cloud Practitioner
* AWS Solutions Architect Associate (Exam Passed)
* Aspiring DevOps & Cloud Engineer
* [LinkedIn](https://www.linkedin.com/in/anna-meggison-8079a1260)

---

### 🏷️ Tags

`#AWS` `#DevOps` `#S3` `#GitHubActions` `#CloudComputing` `#CI/CD` `#BeginnerProject`AWS,AWS skil builder

---



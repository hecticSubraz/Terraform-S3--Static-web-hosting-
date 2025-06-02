
# Terraform-S3 (Static Website Hosting)

This project demonstrates how to use **Terraform** to provision a **static website** hosted on **Amazon S3**.

It automates the creation and configuration of:
- An S3 bucket for hosting the site
- Static website configuration (index and error pages)
- Public access policies
- Uploading HTML files to the bucket

---

##  Live Website

Visit the deployed static site (replace with your actual S3 website endpoint):

http://subrazbuck-07.s3-website-us-east-1.amazonaws.com/


---

##  Tools & Technologies Used

- [Terraform](https://www.terraform.io/) – Infrastructure as Code
- [Amazon S3](https://aws.amazon.com/s3/) – Static web hosting
- [AWS IAM Policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html) – Access management

---

##  What This Terraform Code Does

- Creates an S3 bucket
- Enables static website hosting
- Uploads `index.html` and `error.html` files
- Applies a public read policy to allow website access
- Disables S3 public access blocks

---

##  Project Structure
1. main.tf # Terraform configuration

2.  variables.tf # Variables used in main.tf
3. index.html # Main HTML page
4.  error.html # Error fallback page
5.  .gitignore # Ignore Terraform state and backups



---

##  How to Use This Project

### 1. Clone the repo

$ git clone https://github.com/hecticSubraz/Terraform-S3--Static-web-hosting-.git
cd Terraform-S3--Static-web-hosting-

### 2. Initialize Terraform
$ terraform init

### 3. Apply the Configuration
$ terraform apply

Type yes to confirm.




### Author
Subraz Thapa






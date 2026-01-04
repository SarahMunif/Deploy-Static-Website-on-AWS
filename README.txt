# AWS Static Website Deployment

##  Project Overview
This project demonstrates the deployment of a professional static website using a serverless architecture on **Amazon Web Services (AWS)**.  
By leveraging **S3** and **CloudFront**, the solution delivers a highly available and globally distributed website without relying on traditional servers.

##  Technical Architecture
The solution uses two core AWS services:

* **Amazon S3 (Simple Storage Service):** Stores all website assets, including HTML, CSS, and images.  
* **Amazon CloudFront (CDN):** Serves the website globally with low latency and high availability.

##  Implementation Steps
1. **S3 Configuration:**  
   - Created an S3 bucket for static hosting.  
   - Uploaded the website source files.

2. **CloudFront Distribution:**  
   - Linked the S3 bucket to a CloudFront distribution for global delivery.

3. **Security Policies:**  
   - Applied S3 bucket policies to restrict access only to the CloudFront distribution.

4. **Deployment:**  
   - Verified the live website through the CloudFront endpoint.

##  Live Links
* **CloudFront URL:** [https://d3lrhhgs8w8p2z.cloudfront.net/](https://d3lrhhgs8w8p2z.cloudfront.net/)  
* **S3 Bucket Endpoint:** [http://udacity-2026-demo.s3-website.us-east-1.amazonaws.com/](http://udacity-2026-demo.s3-website.us-east-1.amazonaws.com/)

##  Screenshots
Screenshots documenting the deployment are included in the project folder, covering:  
* S3 Bucket setup and file structure  
* CloudFront distribution settings  
* Permission policies (OAC)

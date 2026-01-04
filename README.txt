#  AWS Static Website Deployment

## 📝 Project Overview
This project demonstrates the deployment of a professional static website using a serverless architecture on Amazon Web Services (AWS). 
By leveraging S3 and CloudFront, the project provides a highly available solution compared to traditional server-based methods.



##  Technical Architecture
The solution is built using two core AWS services:

* **Amazon S3 (Simple Storage Service):** Used as the origin storage for all web assets, including HTML, CSS, and images.
* **Amazon CloudFront (CDN):** Used as a Content Delivery Network to serve the website globally with low latency .


##  Implementation Steps
1.  **S3 Configuration:** Set up a bucket for static hosting and uploaded the website source files.
2.  **CloudFront Distribution:** Linked the S3 bucket to a CloudFront distribution to enable global delivery.
3.  **Security Policies:** Applied S3 bucket policies to restrict access specifically to the CloudFront distribution.
4.  **Deployment:** Verified the live site through the CloudFront endpoint.

## 🔗 Live Link
Access the project here:  
* **CloudFront URL :** [https://d3lrhhgs8w8p2z.cloudfront.net/](https://d3lrhhgs8w8p2z.cloudfront.net/)
* **S3 Bucket Endpoint:** [http://udacity-2026-demo.s3-website.us-east-1.amazonaws.com/](http://udacity-2026-demo.s3-website.us-east-1.amazonaws.com/)
---

## 📸 Project Evidence
Screenshots detailing the configuration process are located in the project folder, covering:
* S3 Bucket setup and file structure.
* CloudFront distribution settings.
* Permission policies (OAC).
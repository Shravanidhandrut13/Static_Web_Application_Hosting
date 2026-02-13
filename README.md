# Static Web Application Deployment using Amazon S3 and CloudFront

## 📌 Project Overview

This project demonstrates the deployment of a static web application
(Tic Tac Toe game) using AWS cloud services.\
Amazon S3 is used for static content storage, and Amazon CloudFront is
used as a Content Delivery Network (CDN) to deliver content globally
over HTTPS.

The solution is scalable, serverless, and requires no compute instance
management.

------------------------------------------------------------------------

## 🏗️ Architecture

Client (Browser) → Amazon CloudFront (CDN) → Amazon S3 (Static Content Storage)
<img width="900" height="443" alt="image" src="https://github.com/user-attachments/assets/1de5ce69-5362-4771-bcb8-98cd87eac820" />

------------------------------------------------------------------------

## 🎯 Objectives

-   Deploy a static web application on AWS
-   Store website files using Amazon S3
-   Deliver content globally using CloudFront CDN
-   Enable secure HTTPS access
-   Implement secure origin access control
-   Follow basic cloud architecture best practices

------------------------------------------------------------------------

## 🛠️ AWS Services Used

### 1️⃣ Amazon S3

-   Created an S3 bucket in the Asia Pacific (Mumbai) region
-   Uploaded HTML, CSS, and JavaScript files
-   Enabled static website hosting

### 2️⃣ Amazon CloudFront

-   Created a CloudFront distribution
-   Configured S3 bucket as origin
-   Set default root object (`index.html`)
-   Enabled HTTPS redirection
-   Used edge locations for low-latency delivery

------------------------------------------------------------------------

## 🚀 Implementation Steps

1.  Created and configured an S3 bucket
2.  Uploaded static web files
3.  Enabled static website hosting
4.  Created a CloudFront distribution
5.  Configured S3 as origin
6.  Tested application using CloudFront domain URL

------------------------------------------------------------------------

## 🔐 Security & Performance Considerations

-   Restricted direct public access to the storage layer
-   Delivered content over HTTPS
-   Improved performance using CDN edge caching
-   Used serverless architecture (no EC2 required)

------------------------------------------------------------------------

## 📈 Outcome

The Tic Tac Toe web application was successfully deployed and is
globally accessible via CloudFront.\
The architecture ensures scalable content delivery with secure access
over HTTPS.

------------------------------------------------------------------------

## 💡 Key Skills Demonstrated

-   AWS S3 configuration
-   CloudFront CDN setup
-   Static website hosting
-   Basic cloud architecture design
-   Deployment troubleshooting

------------------------------------------------------------------------

## 🔗 Outcome

The website was successfully deployed and accessible globally via CloudFront URL. Direct S3 access was restricted, ensuring secure and scalable cloud architecture implementation.

# personal-website

<h1>Simple Personal Website</h1>

<h2>An introductory hands-on project I completed to enhance my practical cloud skills by hosting my personal static website on AWS.</h2>

<hr>

This was my first project built on the cloud, completed alongside Rajdeep Saha's tutorial series ([Rocking AWS for Beginners - Hands-On](https://www.udemy.com/course/rocking-aws-for-beginners-hands-on/)). The series provides guidance on provisioning and configuring essential AWS resources like S3 buckets, CloudFront, Route 53, and AWS Certificate Manager. The project involved the following key steps:  

1. Creating an S3 bucket to host my static website.  
2. Distributing content through CloudFront for enhanced latency and security.  
3. Configuring a custom domain name with Route 53 for improved accessibility.  

<hr>

<h2>An introductory hands-on project I completed to enhance my practical cloud skills by hosting my personal static website on AWS.</h2>

The project follows a simple yet effective architecture leveraging AWS services for hosting and delivering a static website:

<h3>S3 Bucket for Static Website Hosting</h3>
- Used Amazon S3 to store and serve the website content (e.g., HTML, CSS, JavaScript).
- Configured the bucket for static website hosting, making it publicly accessible.

<h3>CloudFront for Content Distribution</h3>
- Implemented Amazon CloudFront as a Content Delivery Network (CDN) to distribute the website content to edge locations, reducing latency for global users.
- Configured security features such as HTTPS using an SSL/TLS certificate from AWS Certificate Manager.

<h3>Route 53 for Domain Name Management</h3>
- Used Amazon Route 53 to register and manage a custom domain.
- Configured DNS records to map the domain name to the CloudFront distribution for seamless access.

<h3>AWS Certificate Manager for SSL/TLS</h3>
- Provisioned an SSL/TLS certificate to enable secure HTTPS communication.

<hr>

<h2>High-Level Workflow</h2>

Content Hosting: Website files are uploaded to the S3 bucket.
Content Delivery: CloudFront retrieves the files from S3 and caches them at edge locations closer to end users.
Domain Resolution: Route 53 directs user traffic to the CloudFront distribution using the custom domain name.
Secure Access: Traffic between users and the website is encrypted using HTTPS, ensured by the certificate from AWS Certificate Manager.

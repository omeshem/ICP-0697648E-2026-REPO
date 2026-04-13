# static website with CDN

## Project Overview
In this project, I built a simple static website using HTML and CSS, hosted it on Amazon S3, and used CloudFront as a CDN to deliver the website.

## Tools Used
- HTML
- CSS
- Amazon S3
- Amazon CloudFront

## Steps I Followed
1. Created the website files locally on my laptop
2. Tested the website in my browser
3. Created an S3 bucket
4. Uploaded `index.html` and `style.css`
5. Enabled static website hosting
6. Added a bucket policy to allow public access
7. Created a CloudFront distribution
8. Tested the CloudFront link successfully

## Challenge I Faced
I had an issue with the S3 bucket policy because the resource ARN was entered incorrectly.

## How I Fixed It
I corrected the bucket policy by removing the repeated ARN and then saved it successfully.

## Outcome
The website was hosted successfully on S3 and delivered through CloudFront.

## Screenshots
See the screenshots folder for proof of setup and deployment.

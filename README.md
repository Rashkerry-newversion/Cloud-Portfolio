# Static Website on AWS S3

## Project Overview

This project demonstrates how to host a simple static website using Amazon S3. It's part of my cloud portfolio to showcase my knowledge of basic cloud infrastructure.

The website is deployed on **AWS S3**, and it includes:

- **`index.html`**: Homepage
- **`error.html`**: Error page

The website is publicly accessible via a custom AWS S3 URL.

## ☁️ Architecture Diagram

![Architecture Diagram](../assets/architecture-diagram.png)

## 🔧 Pre-requisites

- **AWS S3** for static website hosting
- **AWS CLI** (or GUI) for bucket creation and file upload
- **HTML/CSS** for the frontend

## 🚀 Deployment Steps

1. **Create S3 Bucket**:
   - Create a bucket with a globally unique name and select a region.
   - Enable public access (for static website hosting).

2. **Enable Static Website Hosting**:
   - Set `index.html` as the index document.
   - Set `error.html` as the error document.

3. **Upload Website Files**:
   - Upload `index.html` and `error.html` to the bucket.

   **Note**: - Apply a policy to allow public access to your website files.

4. **Access Website**:

   - Access your live site via the URL provided in the S3 static hosting configuration.

## 🖼️ Screenshot

![Screenshot of Live Website](../assets/screenshot.png)

## 🔗 Live Demo

You can view the live site here: [Live Website](http://your-unique-bucket-name.s3-website-<region>.amazonaws.com)

## 📄 Notes

This website is hosted on the AWS Free Tier. The architecture does not include domain management or SSL for now.

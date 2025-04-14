# 🌐 Deploying a Static Website on AWS

This project demonstrates the deployment of a static website using Amazon Web Services (AWS), specifically leveraging Amazon S3 for hosting and Amazon CloudFront for content delivery. It serves as a practical example for hosting static web content in a scalable and cost-effective manner.

## 🧰 Key Features

- **Amazon S3 for Static Hosting**: Utilizes Amazon S3 to host static website files, including HTML, CSS, and JavaScript.
- **CloudFront Integration**: Employs Amazon CloudFront as a Content Delivery Network (CDN) to distribute content globally with low latency.
- **Public Access Configuration**: Configures S3 bucket policies to allow public access to website content.
- **Website Configuration**: Sets up the S3 bucket for static website hosting by specifying index and error documents.

## 📂 Repository Contents

- `README.md`: Project overview and instructions.
- `README.txt`: Additional notes related to the project.
- `pic1.png` to `pic5.png`: Visual aids or screenshots of the deployment process or website interface.

## 🚀 Deployment Steps

1. **Create an S3 Bucket**
   - Set up a new S3 bucket with a unique name.
   - Uncheck "Block all public access" to allow public website hosting.

2. **Upload Website Files**
   - Upload all static files (`index.html`, CSS, JavaScript, images) to the bucket.

3. **Configure for Website Hosting**
   - Enable static website hosting in the bucket properties.
   - Set the index document (e.g., `index.html`) and error document if needed.

4. **Set Bucket Policy**
   - Apply a policy that grants public read access to all objects in the bucket.

5. **Set Up CloudFront Distribution**
   - Create a CloudFront distribution with the S3 bucket as the origin.
   - Configure it for optimized content delivery and caching.

6. **Access Your Website**
   - Use the CloudFront distribution domain to access your static site globally.

## 🛠️ Technologies Used

- **Amazon S3**: For storing and hosting website files.
- **Amazon CloudFront**: For content delivery across the globe.
- **HTML/CSS/JavaScript**: To build the static website.

---

This project offers a foundational understanding of deploying static websites on AWS, perfect for developers or DevOps professionals looking to explore cloud-based hosting.

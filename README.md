## Static Website Hosting on AWS S3
In this project, we will host  secure, fast, and scalable website on S3 with in-built CI/CD to deploy changes automatically, we will use CloudFront distribution for the lowest latency possible.
For this project,
  1. We wil block public access to the origin (S3 bucket) using Origin Access Control or Origin Access Identify.
  2. Implement data encryption both at rest using SSE-S3/ SSE-KMS and in transit using SSL/TLS.
  3. Cache static content and serve them using CloudFront distribution edge location with the lowest possible latency.
  4. Implement highly available and scalable cloud hosting zone and DNS management using Route 53.
  5. Control incoming and outgoing traffic with Web Access Firewall (WAF) and stop common web attacks.
  6. Lastly, build and deploy highly secure and maintainable automation using AWS Code Commit and Code Pipeline.

### Project Architecture
![alt text](https://github.com/Gabinsime75/Project_14--AWS--Static-Website-Hosting-on-AWS-S3/blob/main/Project_14-Architecture.jpg)

### Project outline
  1. Purchase a Domain Name or Use an existing domain.
  2. Create Public Hosted Zone (Optional — External Domains).
  3. Create S3 Buckets for the root domain and the sub-domain.
  4. Upload Website Content to Sub-domain S3 Bucket.
  5. Set up Root Domain for Website Redirect.
  6. Request a Public Certificate from ACM.
  7. Set up CloudFront Distribution for Sub Domain.
  8. Set up CloudFront Distribution for Root Domain.
  9. Route DNS traffic for your domain to your CloudFront distribution (Route 53 or External DNS Provider).
  10. Testing Website Root & Sub-Domain.
  11. Creating a Code Pipeline for CI/CD.
  12. Testing the CodePipeline.
  13. Clean Up.


  ### TEST

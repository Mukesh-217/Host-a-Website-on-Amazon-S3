# Host-a-Website-on-Amazon-S3
OBJECTIVE:

To host a static website exclusively on Amazon S3, providing a simple, scalable, and cost-effective solution for delivering website content.


DESCRIPTION:

This project focuses on hosting a static website using only Amazon S3, AWS's secure and scalable object storage service. The process involves creating an S3 bucket, enabling static website hosting, and configuring the necessary bucket permissions to make the content publicly accessible. By uploading HTML, CSS, and other static assets to S3, the website can be accessed via the S3-generated URL. This method is ideal for static sites that do not require dynamic content processing and allows for easy management of website files through S3's interface or AWS CLI.

No additional AWS services such as CloudFront or Route 53 are used, ensuring simplicity and minimal configuration.


SERVICES UTILIZED:

Amazon S3 is a highly scalable, secure, and durable cloud storage service provided by Amazon Web Services (AWS). It allows users to store and retrieve any amount of data at any time from anywhere on the web. S3 is designed to provide 99.999999999% (11 9’s) durability, making it ideal for storing critical data.

Key Features:-

Scalability: S3 automatically scales to accommodate growing amounts of data without requiring manual intervention.

Durability and Availability: Data is redundantly stored across multiple devices in multiple facilities, ensuring high durability and availability.

Security: S3 offers robust security features, including encryption, access control policies, and integration with AWS Identity and Access Management (IAM) for fine-grained permissions.

Static Website Hosting: S3 can be configured to host static websites by simply enabling the feature on a bucket and uploading HTML, CSS, JavaScript, and other static assets.

Cost-Effectiveness: S3 offers a pay-as-you-go pricing model, making it affordable for both small and large-scale use cases.

Data Management: Features like versioning, lifecycle policies, and cross-region replication help manage data efficiently over time.

Common Use Cases:-
1. Hosting static websites
2. Backup and disaster recovery
3. Content distribution
4. Data archiving
5. Big data analytics

IMPLEMENTATION STEPS:

1. Log into your AWS Management Console.
2. Access Amazon S3 from your AWS Management Console. Create a bucket.
   
   ![image](https://github.com/user-attachments/assets/5d65b2db-b62e-4ebd-b6f9-56e6fb9b4cf7)

3. Make sure ACLs, public access and bucket versioning are enabled.
4. Upload the files into the S3 Bucket.

 ![image](https://github.com/user-attachments/assets/6dc399ee-e0f4-4f1a-9e32-af39f419d69b)

5. In the Properties section of your bucket, enable Static website hosting.
6. There is a URL in the Static website hosting panel, under Bucket website endpoint. Here's what your Static website hosting panel should look like!
   
  ![image](https://github.com/user-attachments/assets/51e50b43-db8e-4be2-8810-256943da43fe)



FINALIZED OUTPUT:

![image](https://github.com/user-attachments/assets/7437acce-3917-4798-bccb-1da6caeb8195)


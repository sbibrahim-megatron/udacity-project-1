# Deploying the Static Website on AWS
Deploying Static website and hosting on cloud is considered to be easy and straight forward using the website information that includes HTML,CSS, JavaScript files. This project will show us how to deploy a static website on AWS.

First, you will create a S3 bucket, configure the bucket for website hosting, and secure it using IAM policies. Next, you will upload the website files to your bucket and speed up content delivery using AWS’s content distribution network service, CloudFront.

Then Lastly, you will access your website in a browser using the unique S3 endpoint.

# Website Files

# Criteria 1 -- The student has created a S3 bucket.

<img width="960" alt="S3 Bucket Created" src="https://user-images.githubusercontent.com/120554885/208499942-4ec3288b-3ea3-4e33-9cef-b9daf17e3c14.PNG">

# Criteria 2 -- All website files should be added to the S3 bucket.

<img width="960" alt="Object Uploaded" src="https://user-images.githubusercontent.com/120554885/208503956-a8b130ce-2c82-4bbf-9573-0a1a404ce22c.PNG">

# Criteria 3 -- The permission access to the bucket should be configured to allow public access.

<img width="960" alt="Secure bucket through IAM" src="https://user-images.githubusercontent.com/120554885/208504176-19337e96-1269-41ea-9bf7-53d7a63b5f40.PNG">

# Website Distribution

# Criteria 5 -- The website should be distributed via Cloudfront.

<img width="949" alt="Website Configuration" src="https://user-images.githubusercontent.com/120554885/208504575-ba27150f-d011-47fa-a22c-bd366064634e.PNG">

Site Screen Shot / https://d5ptsiqfn0b5o.cloudfront.net/ / http://my-483775213643-bucket.s3-website.us-east-1.amazonaws.com/ / https://my-483775213643-bucket.s3.amazonaws.com/index.html

<img width="960" alt="Access Website Using CloudFront domain name" src="https://user-images.githubusercontent.com/120554885/208505109-283be581-1f4c-458d-b377-97021f5d1147.PNG">

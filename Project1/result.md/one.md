# Create a static website and host it on an S3 bucket with public read policy assigned, using cloud front for CDN.

## 1 Log in to AWS account and navigate to S3 bucket 
![](./ss/S3/Screenshot%202024-05-10%20at%2020.16.02.png)

## 2 Click on 'Create bucket' button
![](./ss/S3/Screenshot%202024-05-10%20at%2020.17.01.png)

## 3 Select 'General Purpose' for bucket type, input desired bucket name for 'Bucket name', leave other settings as is, scroll to bottom and click 'Create bucket' button
![](./ss/S3/Screenshot%202024-05-10%20at%2020.18.06.png)
![](./ss/S3/Screenshot%202024-05-10%20at%2020.18.14.png)

## 4 Navigate to the created bucket, to upload website files
![](./ss/S3/Screenshot%202024-05-10%20at%2020.18.45.png) 

## 5 Click on 'Upload' button, click on 'Add files' and 'Add folder' to upload website contents and watch out for confirmation after successful upload
![](./ss/S3/Screenshot%202024-05-10%20at%2021.30.11.png)
![](./ss/S3/Screenshot%202024-05-10%20at%2021.30.45.png)

## 6 Navigate to CloudFront to create a distribution
![](./ss/S3/Screenshot%202024-05-10%20at%2021.33.44.png)

## 7 Select 'Origin domain', select 'origin access control settings (recommended) for Origin access option, Leave other settings as is
![](./ss/S3/Screenshot%202024-05-10%20at%2021.34.07.png)

## 8 Edit Bucket Policy permissions in S3 bucket, navigate to CloudFront, copy DNS addess and check for successful deployment.  
![](./ss/S3/Screenshot%202024-05-10%20at%2021.38.37.png)
![](./ss/S3/Screenshot%202024-05-11%20at%2017.20.25.png)
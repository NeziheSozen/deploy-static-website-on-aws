# deploy-static-website-on-aws
This is the first project of Cloud Developer Course on Udacity

# Project Steps

## Created S3 Bucket
![Created s3 bucket](img/created_buckets.PNG "Created s3 bucket")

## S3 Bucket Policy
![Bucket Policy](img/bucket_policy.PNG "Created s3 bucket policy")

## Created S3 Bucket's Content Files
![Bucket Content Files](img/bucket_content_files.PNG "Bucket Content Files")

## CloudFront Distributions
![Cloud front distributions](img/created_buckets.PNG "CloudFront Distributions")

# Access Website in Web Browser

1. Open a web browser like Google Chrome, and paste the copied CloudFront domain name:

https://d179zo7kqaata4.cloudfront.net

![Cloud Front Preview](img/1.PNG "Cloud Front Preview")

2. Access the website via website-endpoint

http://my-nanodegreeproject01-bucket.s3-website-us-east-1.amazonaws.com/

![Website Endpoint Preview](img/2.PNG "Website Endpoint Preview")

3. Access the bucket object via its S3 object URL

https://my-nanodegreeproject01-bucket.s3.amazonaws.com/index.html

![S3 object URL Preview](img/3.PNG "S3 object URL Preview")

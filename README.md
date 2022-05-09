# website-deploy-s3

## What it does
This repo demonstrates a CI/CD pipeline that deploys a vuejs website to s3

## Prerequisits
-   You have an aws account 
-   Fork this repo

## How to run?
-   Created a bucket under a name you can use eg.my-website-8001
-   Create an iam user with credentials to give the workflow permission to deploy your repo
-   Replace bucket policy with the contents of bucket-policy.json file
-   Enable Static website hosting under the properties tab of the bucket and hosting type of "Host a static website"
-   Enable check-box of Everyone (public access) for objects. This is under Access control list (ACL) of the permissions tab
-   Enable public access under the permissions tab of your s3 bucket
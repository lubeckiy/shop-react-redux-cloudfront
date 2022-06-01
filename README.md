# __Task 2__

Task [description here](https://github.com/EPAM-JS-Competency-center/cloud-development-course-initial/blob/main/2_serving_spa/task.md)

Task due date / deadline date - 2022-05-16 07:00 / 2022-05-30 01:59 (GMT+3)

SELF CHECK: __5 points__

-----------
## __Evaluation criteria__

- [x] **0** - Nothing has been done. __(Link to repository is not provided. Nothing to check.)__
- [x] **3** - S3 bucket has been created and configured properly. The app has been uploaded to the bucket and is available though the Internet. Nothing else has been done. __(Link to S3 bucket/website is provided. There is no Pull Request in the YOUR OWN frontend repository.)__
- [x] **4** - In addition to the previous work a CloudFront distribution is created and configured properly and the site is served now with CloudFront and is available through the Internet over CloudFront URL, not S3-website link (due to changes in bucket’s policy...). __(Link to CloudFront website is provided. S3-website shows 403 Access Denied error. There is no Pull Request in the YOUR OWN frontend repository.)__
- [x] **5** - Serverless-finch and serverless-single-page-app plugins are added and configured. The app can be built and deployed by running npm script command. __(Link to CloudFront website is provided. PR with all changes is submitted in the YOUR OWN frontend repository and its link is provided for review.)__
------------
## __Report__

### __Task 2.1 Manual deployment__

S3 link - http://backet-for-fe-app.s3-website.eu-central-1.amazonaws.com/

Cloudfront link - https://d25pa8zi69fms2.cloudfront.net/

### __Task 2.2 Automated deployment using serverless-finch + serverless single-page-app plugins__

S3 link - http://backet-for-fe-app-auto-2.s3-website-us-east-1.amazonaws.com/

Cloudfront link - http://backet-for-fe-app-auto-2.s3-website-us-east-1.amazonaws.com/

## __Summary__

__All tasks have been done.__

## __How to deploy__

1. Clone repository. (git clone ...)
2. Change branch to __task-2-sls__ (git checkout task-2-sls)
3. Install dependencies. (npm i)
4. Change Service and Bucket Name in serverless.yml
5. Run command: __npm run cloudfront:build:deploy__

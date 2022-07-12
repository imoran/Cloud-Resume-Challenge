# The Cloud Resume Challenge - AWS

- [x] **1. Certification** </br>
Your resume needs to have the AWS Cloud Practitioner certification on it

- [x] **2. HTML** </br>
Your resume needs to be written in HTML

- [x] **3. CSS** </br>
Your resume needs to be styled with CSS

- [x] **4. Static Website** </br>
Your HTML resume should be deployed online as an Amazon S3 static website (S3)

- [x] **5. HTTPS** </br>
The S3 website URL should use HTTPS for security (CloudFront)

- [x] **6. DNS** </br>
Point a custom DNS domain name to the CloudFront distribution, so your resume can be accessed at a domain name of your choosing (Amazon Route 53 + CloudFront + AWS Certificate Manager)

- [ ] **7. JavaScript** </br>
Your resume webpage should include a visitor counter that displays how many people have accessed the site

- [ ] **8. Database** </br>
The visitor counter will need to retrieve and update its count in a database somewhere (DynamoDB)

- [ ] **9. API** </br>
Do not communicate directly with DynamoDB from your JavaScript code. Instead, you will need to create an API that accepts requests from your web app and communicates with the database (API Gateway + Lambda)

- [ ] **10. Python** </br>
You will need to write a bit of code in the Lambda function (boto3 library for AWS)

- [ ] **11. Tests** </br>
You should also include some tests for your Python code

- [ ] **12. Infrastructure as Code** </br>
You should not be configuring your API resources - the DynamoDB table, the API Gateway, the Lambda function -- manually, by clicking around in the AWS console. Instead, define them in an AWS Serverless Application Model (SAM) template and deploy them using the AWS SAM CLI

- [ ] **13. Source Control** </br>
You do not want to be updating either your back-end API or your front-end website by making calls from your lapto**p. You want them to update automatically whenever you make a change to the code

- [ ] **14. CI/CD (Back-end)** </br>
Set up GitHub Actions such that when you push an update to your SAM or Python code, your Python tests get run. If the tests pass, the SAM application should get packaged and deployed to AWS

- [ ] **15. CI/CD (Front-end)** </br>
  Create a second GitHub repository for your website code. Create GitHub Actions such that when you push new website code, the S3 bucket gets automatically updated

- [ ] **16. Blog Post** </br>
In the text of your resume, you should link a short blog post describing some things you learned while working on this project. [Blog](https://isis-from-sf.hashnode.dev/)
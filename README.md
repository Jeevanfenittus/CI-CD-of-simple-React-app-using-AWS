# React App Deployment on AWS

 Features
- React app displaying a sample message
- CI/CD pipeline using GitHub Actions
- Automatic deploy to S3 and CloudFront
- Jest test example

 Running Locally
1. Clone the repo:
2. Install dependencies:
3. Run the app locally:


 Deployment
- CI/CD pipeline deploys automatically on push to `main`.
- Workflow file: `.github/workflows/deploy-s3.yml`
Live Demo
- S3 URL: http://project-bucket-react.s3-website-ap-south-1.amazonaws.com
- CloudFront URL: https://d1234abcd.cloudfront.net

 Notes
- AWS credentials are not included. Uses OIDC role for secure deployment.
- To deploy in your own account, update IAM role and bucket in workflow.

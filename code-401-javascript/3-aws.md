# Code 401 Javascript Setup

## Cloud Service Providers - Amazon AWS

As part of the 401 Curriculum and beyond, you'll be using various cloud service providers to deploy code. Here, we'll install the AWS command line tools

> Optionally, you may go to <https://aws.amazon.com> and create an account. While you will not be charged, Amazon will want a Credit Card as validation. You will get $200 in free usage credits when you create your account

1. Install the AWS CLI tools, by running this command in your terminal:
   - `brew install awscli`
1. Confirm proper installation
   - `aws --version`
   - You should see output with these versions or higher:

   ```bash
   aws-cli/2.0.19 Python/3.8.3 Linux/4.19.104-microsoft-standard botocore/2.0.0dev23
   ```
1. Install the Elastic Beanstalk CLI tools, by running this command in your terminal:
   - `brew install awsebcli`
1. Confirm proper installation
   - `eb --version`
   - You should see output with these versions or higher:

   ```bash
   EB CLI 3.20.3 (Python 3.10.)
   ```

---

### [⇐ Previous](./2-netlify.md) | [Next ⇒](./4-postgres.md)

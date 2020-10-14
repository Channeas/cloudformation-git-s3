# cloudformation-git-s3

## About

This is a [CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html) template that pulls code from an external Git repo (as of right now, either Github or Bitbucket) and deploys that code in an S3 bucket. If the S3 bucket is public, it essentially acts as your own version of [Vercel.com](https://vercel.com/)

To do this, a [CodeStar Connection](https://docs.aws.amazon.com/codestar-connections/latest/APIReference/Welcome.html) is required

**Note: This template does not build code, it just copies it**

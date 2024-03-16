Step 1: To install global serverless package 

 npm install -g serverless 

Step 2 : To create Serverless pre-template project 

  serverless create --template aws-nodejs 

Step 3: To configure Aws creditential through serverless cli command 

  serverless config credentials --provider aws --key x....xx.. --secret x.......

  Note : Please make sure IAM user has full access otherwise will face deployment issue

Step 4 : Final step would be deployment 

   serverless deploy --stage development --region ap-south-1
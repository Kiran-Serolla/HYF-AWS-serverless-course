## Mandatory assignments

**Assignment 1:**

What is an ARN: `?`
ARN stands for Amazon Resource Name. ARNs uniquely identify AWS resources.
An ARN consists of partition, service, region, account id and resource-id.

response from command :
{
    "Account": "744286628539", 
    "UserId": "744286628539", 
    "Arn": "arn:aws:iam::744286628539:root"
}

**Assignment 2:**

Response from the command: `?`
'us-east-1' is a supported AWS Region


**Assignment 3:**

Command to upload file with the AWS CLI: `?`
response from command 'aws s3 ls:'
2022-10-07 09:43:11 hyf-week1-clibucket
2022-10-07 09:40:59 hyf-week1-console-kiran

command to upload file to bucket from CLI:
aws s3 mv hello-world.txt s3://<Bucket Name>

Command to create a presigned URL: `?`
aws s3 presign s3://<Bucket name>/<File name>

Command to delete your bucket with the AWS CLI: `?`

Can you simply delete a CloudFormation bucket? : `?`

**Assignment 4 (Optional):**

Command to deploy your CloudFormation template using the AWS CLI: `?`
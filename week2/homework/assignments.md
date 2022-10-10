## Mandatory assignments

**Assignment 4 & 5:**

Sync your changes to s3 and write down your s3 bucket url.

bucket url: `?`
http://hyf-hosting-webapp-bucket.s3-website-us-east-1.amazonaws.com

**Assignment 6:**

Right now, the website does not support HTTPS. Explain which other AWS service needs to be integrated in order to achieve this.

service name: `?`
Cloud Front

**Assignment 7:**

Write down the main cost factors for S3

brief description: `?`
three primary costs associated with S3: storage cost charged per GB per month or hour, API cost for operation of files, and data transfer cost outside the AWS region.

**Assignment 8:**

How much would it cost to store 51TB on S3? 
$ 0,022 per GB

Price: `?`

**Assignment 9:**

How much would hosting your website on S3 cost?

The total cost of hosting your static website on AWS will vary depending on your usage. Typically, it will cost $1-3/month if you are outside the AWS Free Tier limits. If you are eligible for AWS Free Tier and within these limits, hosting your static website will cost around $0.50/month.

**Assignment 10:**

Write down a brief use case on when S3 could be used for a data engineering assignment:

use case: `?`

## Optional assignments:

**Assignment 11:**

What can be done to reduce the pricing for S3 when hosting a large number of files?

brief description: `?`
1. Identify large buckets that you aren’t aware of
2. Find and eliminate incomplete multipart upload bytes
3. Increase use of S3 storage classes
4. Reduce the number of noncurrent versions retained


**Assignment 12:**

There are many security features built into S3. Find your favourite feature, documentation for it, and explain briefly why.

To protect your data in Amazon S3, by default, users only have access to the S3 resources they create. You can grant access to other users by using one or a combination of the following access management features: AWS Identity and Access Management (IAM) to create users and manage their respective access; Access Control Lists (ACLs) to make individual objects accessible to authorized users; bucket policies to configure permissions for all objects within a single S3 bucket; and Query String Authentication to grant time-limited access to others with temporary URLs. Amazon S3 also supports Audit Logs that list the requests made against your S3 resources for complete visibility into who is accessing what data.

brief description of favourite security feature: `?`


Block Public Access:
 S3 Block Public Access settings override S3 permissions that allow public access, making it easy for the account administrator to set up a centralized control to prevent variation in security configuration regardless of how an object is added or a bucket is created.

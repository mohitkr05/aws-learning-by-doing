# Creating a static website using S3

1. Upload your code in the S3 bucket

![alt text](images\s3-static-web-1.png)

2. Go to properties and change the settings to create a static website

![alt text](images\s3-static-web-2.png)

3. Set up redirection rules if required, for example the following redirection rule  defines how to handle requests and redirect them based on certain conditions.  

1. Condition:
   - "HttpErrorCodeReturnedEquals": Specifies an HTTP error code. If the request results in this error code, the redirection will be applied.

2. Redirect:
   - "Protocol": Whether to use "http" or "https" for the redirect.
   - "ReplaceKeyPrefixWith": Replaces the beginning of the object key with this value.
   - "ReplaceKeyWith": Replaces the entire object key with this value.

In simple terms, this rule says: "If a request meets certain conditions (like a specific error code or URL prefix), redirect it to a different URL, potentially changing the protocol, domain, and/or path in the process."

Would you like me to explain any part of this in more detail?

```json
[
  {
    "Condition": {
      "HttpErrorCodeReturnedEquals": "403"
    },
    "Redirect": {
      "Protocol": "https",
      "HttpRedirectCode": "301"
    }
  }
]
```

3. After this an URL will be generated


![alt text](images\s3-static-web-3.png)

4. Now the next step is to enable the Public access.
> Public access is granted to buckets and objects through access control lists (ACLs), bucket policies, access point policies, or all. In order to ensure that public access to all your S3 buckets and objects is blocked, turn on Block all public access. These settings apply only to this bucket and its access points


![alt text](images\s3-static-web-4.png)

5. Create a bucket policy

![alt text](images\s3-static-web-5.png)
```json
{
    "Version": "2012-10-17",
    "Id": "Policy1720919040547",
    "Statement": [
        {
            "Sid": "Stmt1720919038529",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::awsbootcampbucket/*"
        }
    ]
}

```

6. Access the URL


However, this is not a better use case as we have to allow access to the S3 bucket.


7. Attaching a CloudFront endpoint, create a new CloudFront endpoint

![alt text](images\s3-static-web-7.png)



8. Create a new origin access control

![alt text](images\s3-static-web-6.png)

![alt text](images\s3-static-web-8.png)


![alt text](images\s3-static-web-9.png)



![alt text](images\s3-static-web-10.png)


9. Update the policy of the S3 bucket


```json

{
    "Version": "2008-10-17",
    "Id": "PolicyForCloudFrontPrivateContent",
    "Statement": [
        {
            "Sid": "AllowCloudFrontServicePrincipal",
            "Effect": "Allow",
            "Principal": {
                "Service": "cloudfront.amazonaws.com"
            },
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::awsbootcampbucket/*",
            "Condition": {
                "StringEquals": {
                    "AWS:SourceArn": "arn:aws:cloudfront::652897695890:distribution/E2RMMYGIGIY6F1"
                }
            }
        }
    ]
}


```
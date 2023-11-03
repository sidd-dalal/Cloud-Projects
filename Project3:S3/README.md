Hosting a Static Website on S3:

1. Create a bucket with a globally unique name and uncheck block public access.
2. Upload an index.html file in the bucket.
3. Add a bucket policy in order for it to be viewed from anywhere on the internet

Policy:

{

    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": [
                "s3:GetObject"
            ],
            "Resource": [
                "arn:aws:s3:::<Bucket-Name>/*"
            ]
        }
    ]
}
  

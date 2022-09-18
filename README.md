## Mirotron
This is a script that will sync a local directory to an s3 bucket and optionally configure Route 53 and cloudfront

## Features

Mirotron currently has the following features:

- All S3 buckets under the aws profile can be listed 
- All objects in a specified S3 bucket can be listed
- An operation to Create an new bucket that has a PublicReadGetObject policy to enable website hosting
- Sync directory to s3
- Set a specific AWS profile to use by typing --profile=<profilename>
- configure route 53 domain



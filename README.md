# Use AWS CLI to Operate an S3 Bucket

## Install AWS CLI
[AWS documantation](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

## Authentication
### Using IAM Roles
- Create an IAM Role with S3 permissions.
- Attach it to your EC2 instance.
- Run S3 commands without `aws configure`.

## Usage
- Upload a File to S3
```sh
aws s3 cp test.txt s3://your-bucket-name/
```

- Download a File from S3
```sh
aws s3 cp s3://your-bucket-name/test.txt .
```

- Delete a File from S3
```sh
aws s3 rm s3://your-bucket-name/test.txt
```

## Concept
[Visit (takehika0129.github.io)](https://takehika0129.github.io/takehika-github-pages/reviews/prototype8.html)

## License
You are free to use this code for personal and educational purposes. Commercial use and redistribution are not allowed.
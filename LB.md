# An Intro introduction to AWS Load Balancing and Autoscaling in the Cloud:

Welcome to the most recent installment of our AWS Tutorials!

The following will be a continuation of our last AWS tutorial where we created our first VPC. 
In this tutorial we will be creating a load balancer which will attach to our previous VPC.
If you like to visit the previous tutorial please use the following link: [AWS::VPC](https://github.com/mindmotivate/multicloudclass/blob/main/aws-vpc-tutorial.md) #<- change link

![image](https://github.com/ldatareserve/AWSdocumentation/assets/134747179/c68b86e5-8ecd-4d1d-9c1f-9f177d70c794)

Path Shown: ***Server (in Private Subnet) -> NAT Gateway -> Internet Gateway -> Internet***


1. In the Amazon EC2 console, navigate to *Security Groups*.
2. Choose *Create Security Group*.
3. Enter a name and description for the security group.
4. For *VPC*, select the VPC you previoulsy created.<br>

    *On VPC click on the x and replace the VPC that is labeled

   # 3. Create a Launch Template

- Navigate to the Amazon EC2 console,
- Choose *Launch Template* from left side menu-
- Click on Create launch templates

## Videos

- [YouTube Video 1](https://www.youtube.com/watch?v=8TlukLu11Yo)
- [YouTube Video 2](https://www.youtube.com/watch?v=pT7us47auGQ)

> This is a basic guide; explore other configuration options available.
> Find more information about EC2 in the [AWS documentation](https://docs.aws.amazon.com/).
> Source: [GitHub](https://github.com/giuseppeporcelli/smlambdaworkshop) (subject to license - [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)).






In the example above, replace the image URL (https://example.com/ec2-instance.png) with the actual URL of your image. The emoji :rocket: will render as a rocket emoji. You can replace it with any other emoji shortcode supported by Markdown processors.

:rocket: Happy Cloud Computing!

### HCL example
```hcl
module "ec2_instance" {
  source  = "terraform-aws-modules/ec2-instance/aws"

  name = "single-instance"

  instance_type          = "t2.micro"
  key_name               = "user1"
  monitoring             = true
  vpc_security_group_ids = ["sg-12345678"]
  subnet_id              = "subnet-eddcdzz4"

  tags = {
    Terraform   = "true"
    Environment = "dev"
  }
}
```

### JSON example
```json
{
    "Resources": {
        "HelloBucket": {
            "Type": "AWS::S3::Bucket"
        }
    }
}
```

### YAML example
```yaml
Resources:
  HelloBucket:
    Type: 'AWS::S3::Bucket'
```

| Month    | Savings |
| -------- | ------- |
| January  | $250    |
| February | $80     |
| March    | $420    |

| Item              | In Stock | Price |
| :---------------- | :------: | ----: |
| Python Hat        |   True   | 23.99 |
| SQL Hat           |   True   | 23.99 |
| Codecademy Tee    |  False   | 19.99 |
| Codecademy Hoodie |  False   | 42.99 |

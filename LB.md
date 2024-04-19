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

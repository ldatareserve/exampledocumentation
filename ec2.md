![download](https://github.com/mindmotivate/EC2/assets/130941970/59484b98-03a8-4ec1-952e-8bf6b0b857d1)

# Building an EC2 Instance in AWS

## Prerequisites
- An AWS account
- Basic understanding of the [AWS console](https://aws.amazon.com/console/)
- Familiarity with [SSH](https://en.wikipedia.org/wiki/Secure_Shell) (Linux) or [Remote Desktop](https://en.wikipedia.org/wiki/Remote_Desktop_Protocol) (Windows)

## Step 1: Choose an Amazon Machine Image (AMI)
An AMI is a preconfigured template that includes the operating system, software, and configuration settings for your EC2 instance. Choose from a variety of AMIs, such as [Amazon Linux 2](https://aws.amazon.com/amazon-linux-2/), [Ubuntu](https://ubuntu.com/), and [Windows Server](https://www.microsoft.com/en-us/cloud-platform/windows-server).

1. Open the [AWS Management Console](https://aws.amazon.com/console/) and navigate to the EC2 service.
2. Click on **Launch Instance**.
3. Select an AMI from the list based on your requirements. For this guide, we'll use the [Amazon Linux 2 AMI](https://aws.amazon.com/amazon-linux-2/).

## Step 2: Configure the Instance
Configure the following settings for your EC2 instance:

- **Instance Type:** Determine the CPU, memory, and storage resources for your workload.
- **Network Settings:** Specify the subnet and security group for your instance.
- **Key Pair:** Create or use an existing key pair for SSH authentication.

Additional configuration options include storage and tags.

## Step 3: Launch the Instance
Click on **Launch** after configuring your settings. The instance will take a few minutes to launch.

## Step 4: Connect to your Instance
Connect to your instance using SSH (Linux) or Remote Desktop (Windows).

**To connect using SSH:**
```bash
ssh -i <key_pair>.pem <user>@<public_ip>
```

## Step 5: Install and Configure Software

Install and configure the necessary software for your application (e.g., Apache, Nginx for a web server).

## Step 6: Terminate the Instance

When done, terminate the instance to avoid charges.

1. Open the AWS Management Console and navigate to the EC2 service.
2. Select the instance, click on **Actions > Terminate**.

*Note: You'll be charged for the running time, even if not actively using the instance.*

## Useful Resources

- [AWS EC2 User Guide](https://docs.aws.amazon.com/ec2/)
- [AWS EC2 Launch Instance Wizard](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/launching-instance.html)
- [AWS Documentation](https://docs.aws.amazon.com/)

## Videos

- [YouTube Video 1](https://www.youtube.com/watch?v=8TlukLu11Yo)
- [YouTube Video 2](https://www.youtube.com/watch?v=pT7us47auGQ)

## Additional Notes

> This is a basic guide; explore other configuration options available.
> Find more information about EC2 in the [AWS documentation](https://docs.aws.amazon.com/).
> Source: [GitHub](https://github.com/giuseppeporcelli/smlambdaworkshop) (subject to license - [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)).

:rocket: Happy Cloud Computing!


In the example above, replace the image URL (`https://example.com/ec2-instance.png`) with the actual URL of your image. The emoji `:rocket:` will render as a rocket emoji. You can replace it with any other emoji shortcode supported by Markdown processors.

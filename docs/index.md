# Infrastructure as Code
This repo contain the necessary Terraform scripts to build out the AWS infrastructure as outlined in my article, *[DevOps Automation and IaC](https://medium.com/devopslinks/devops-automation-and-iac-c007c3c0d172)*

Some of the code snipit is based on the following excellent work (thanks guys!)

- *[Hackernoon - Manage AWS VPC as Infrastructure as Code with Terraform](https://hackernoon.com/)*

- *[Nick Carlton - Terraform: AWS VPC with Private and Public Subnets](https://nickcharlton.net/posts/terraform-aws-vpc.html)*

## AWS Infrastructure
---
Below is a diagram of the AWS infrastructure we will setup using Terraform.

<img src="images/iac-aws.png" width="800" align="left"/>

## Source Code
---
[TF-IAC-2019 Code](https://github.com/bissessr/TF-IAC-2019/)


## Setup Instructions
---
After completing the pre-requisites use the instructions below to begin the setup process.

1. Setup your AWS credentials
2. Create new folder for your terraform scripts and supporting files
3. Change to the folder
4. Initialize and sync GIT repository
5. Run terraform init
6. Run terraform plan to test your script
7. Terraform Plan — No errors
8. If all is good, run *terraform apply* to kick off the script


## More Information
---
Checkout my articles on *[Medium](http://medium.com/@cloud_guy1)*

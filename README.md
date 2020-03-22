#Terraform AWS Project


Manual installation: Download from here: https://www.terraform.io/downloads.html
for windows: in powershell admin console "choco install terraform"
for mac use "brew install terraform"

https://www.terraform.io/docs/providers/aws/index.html#shared-credentials-file


Create a new user terraform_user in AWS, set access type programmatic access, assign policy with admin access

aws configure or
mkdir .aws
create afile with name credentials
for mac touch .aws/credentials

[terraform]
aws_access_key_id = xxxxxxxxxxxxxxxxxxx
aws_secret_access_key = xxx/xxxxxxxxxxxxx/xxxx

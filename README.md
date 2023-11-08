# terraform-training

### Prerequisite
Install and configure the following:
1. AWS CLI, [doc](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
2. Terraform, [doc](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

### Getting started

1. Generate a key pairs  
cd into keys directory with command `cd keys`  
```
ssh-keygen -t rsa -b 4096 -C "training-key"
```

1. Deploy
```
terraform init
```
```
terraform validate
```
```
terraform plan -out tfplanfile
```
```
terraform apply tfplanfile
```

1. Destroy  
```
terraform destroy
```

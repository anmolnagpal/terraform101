<p align="center"><img src="https://user-images.githubusercontent.com/4303310/42405951-88afac1e-81af-11e8-9d78-f694c6e982f6.png" /></p>

> Terraform for beginners 

### Install terraform 
For MAC OS -
```sh
brew install terraform
```
### Export AWS secret keys, else define them in `aws-provider.tf` -
```sh
export AWS_ACCESS_KEY_ID=AKIA********
export AWS_SECRET_ACCESS_KEY=8s8v1lT*******************
export AWS_DEFAULT_REGION=us-east-1
```
### Initialize terraform - 
```sh
terraform init
```
## Change variables "orgname" & "environ" in `variables.tf` as per your requirement.

### Plan (shows execution plan) - 
```sh
terraform plan -out terraform-plan-key
```
### Apply (Creates the defined infrastructe) - 
```sh
terraform apply terraform-plan-key
```
### Destroy the infra which we build just now - 
```sh
terraform destroy
```

## 👬 Contribution
- Open pull request with improvements
- Discuss ideas in issues

- Reach out with any feedback [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/anmol_nagpal.svg?style=social&label=Follow%20%40anmol_nagpal)](https://twitter.com/anmol_nagpal)

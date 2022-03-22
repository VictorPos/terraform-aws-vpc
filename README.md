# Terraform AWS VPC Module 

### Usage 
```
module "vpc" {
    source = "VictorPos/vpc/aws"
    cidr_block = "10.0.0.0/16"
}
```
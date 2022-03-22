# Terraform AWS VPC Module 

### Usage 
```
module "vpc" {
    source = "VictorPos/vpc/aws"
    cidr_block = "10.0.0.0/16"
    tags = {
        Name = "Dev"
        private_subnets_cidr = ["10.0.1.0/24"]
    }
}
```
# AWS VPC module for Terraform

A simple VPC module for Terraform

## Usage

```bash
module "vpc" {
  source        = "github.com/qba73/tst-tf-vpc"
  name          = "vpc_name"
  cidr          = "10.0.0.0/16"
  public_subnet = "10.0.1.0/24"
}
```

See `interface.tf` for additional configurable variables

## License

MIT


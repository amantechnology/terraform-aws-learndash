# terraform-aws-learndash

Terraform module to deploy WordPress with LearnDash LMS installed. This is useful for someone who wants to experiment hosting LearnDash LMS on AWS.

## Get Started

You need an AWS account and knows how to use module in Terraform.

```
module "demo" {
  source  = "amantechnology/learndash/aws"
  version = "0.1.0"
}
```

## Reference

* [Create AWS account](https://aws.amazon.com/free/)
* [Use registry modules in configuration](https://developer.hashicorp.com/terraform/tutorials/modules/module-use#module-use)

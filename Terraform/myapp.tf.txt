# Configure the AWS Provider
provider "aws" {
    access_key = "${}"
    secret_key = "${}"
    region = "us-east-1"
}

resource "aws_vpc" "myapp" {
     cidr_block = "10.100.0.0/16"
}

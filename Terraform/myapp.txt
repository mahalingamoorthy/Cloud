# Configure the AWS Provider
provider "aws" {
    access_key = "${KIAIQTAGU7H5I4WJ2YQ}"
    secret_key = "${sFIQbjjXSHS4Leittl0zPRlWK1tju6iEVPGf+SXk}"
    region = "us-east-1"
}

resource "aws_vpc" "myapp" {
     cidr_block = "10.100.0.0/16"
}
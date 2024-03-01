<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-project/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Simple Terraspace Project

Simple Terraspace Project is used to show how to migrate from Terragrunt to Terraspace.

## Usage

Change the bucket in [config/terraform/backend.tf](config/terraform/backend.tf#L3) to a bucket that matches the [boltops-learn/terragrunt-project](https://github.com/boltops-learn-docs/terragrunt-project) [terragrunt.hcl](https://github.com/boltops-learn-docs/terragrunt-project/blob/master/terragrunt.hcl#L18) file

Install dependencies

    bundle

List modules and stacks

    terraspace list

Deploy infrastructure

    terraspace up demo

## Video

[![Watch the video](https://uploads-learn.boltops.com/bdhh9vbc0lrk90fih1482se9oa4d)](https://learn.boltops.com/courses/terraspace-and-terragrunt/lessons/terragrunt-to-terraspace-step-by-step-migration)

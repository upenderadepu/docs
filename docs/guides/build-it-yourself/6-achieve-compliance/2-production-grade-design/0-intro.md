---
pagination_label: Production-grade Design
---

# Intro to Production-grade Design

In [core concepts](../1-core-concepts/0-intro.md) we discussed the basics of the AWS Foundations Benchmark. Although it's possible to achieve
compliance with the Benchmark by manually configuring each setting in the web console or entering the CLI commands, we
strongly discourage this approach. It precludes [the myriad benefits of using code to manage infrastructure](https://gruntwork.io/guides/foundations/how-to-use-gruntwork-infrastructure-as-code-library/#infrastructure-as-code).

Instead, we advise using [Terraform](https://www.terraform.io) (or similar tools, such as
[CloudFormation](https://aws.amazon.com/cloudformation/) or [Pulumi](https://www.pulumi.com/) to configure cloud
resources programmatically. This section will cover the Terraform resources you can use to implement each of the
recommendations. We assume that you're familiar with the basics of Terraform. If you aren't, read our
[Introduction to Terraform blog post](https://blog.gruntwork.io/an-introduction-to-terraform-f17df9c6d180), or pick
up the [2nd
edition of Terraform Up & Running](https://blog.gruntwork.io/terraform-up-running-2nd-edition-early-release-is-now-available-b104fc29783f).


<!-- ##DOCS-SOURCER-START
{"sourcePlugin":"Local File Copier","hash":"6e07b1fda93b464943f4c9e20a9ac129"}
##DOCS-SOURCER-END -->
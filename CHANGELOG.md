## terraform-aws-tardigrade-transit-gateway Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

### [2.6.0](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/2.6.0)

**Released**: 2024.10.08

**Summary**:

*   Supports configuring vpc routes with prefix list destinations

### [2.5.0](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/2.5.0)

**Released**: 2024.09.30

**Summary**:

*   Adds support to tgw and vpc attachments for security group referencing

### [2.4.1](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/2.4.1)

**Released**: 2024.08.26

**Summary**:

*   Adds source for aws provider to better support nested modules with aliased
    providers

### [2.4.0](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/2.4.0)

**Released**: 2024.08.26

**Summary**:

*   Supports associating managed prefix lists to a transit gateway route table

### [2.3.1](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/2.3.1)

**Released**: 2024.08.21

**Summary**:

*   Improves compatibility with terraform <1.6 using ternary to short-circuit evaluation
    instead of try
*   Updates terraform provider version for when `options` was added to `aws_ec2_transit_gateway_peering_attachment`

### [2.3.0](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/2.3.0)

**Released**: 2024.08.20

**Summary**:

*   Manages tgw route table associations for tgw peering connections
*   Supports `options` input for peering attachment resource

### [2.2.0](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/2.2.0)

**Released**: 2023.07.18

**Summary**:

*   Supports auto-accept configurations for cross-account vpc attachments

### [2.1.0](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/2.1.0)

**Released**: 2022.03.29

**Summary**:

*   Supports creating VPC Attachments in appliance mode using the argument, `appliance_mode_support`.

### [2.0.0](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/2.0.0)

**Released**: 2021.12.29

**Summary**:

*   Removes variables in cross-account-vpc-attachment module that were used to
    create a dependency so the attachment would succeed. These variables are no
    longer needed, presumably due to new retry functionality in the AWS provider.
*   Uses `configuration_aliases` instead of empty provider blocks.
*   Bumps minimum terraform version to 0.15 for the cross-account and cross-region
    modules.

### [0.0.0](https://github.com/MetroStar/terraform-aws-tardigrade-transit-gateway/releases/tag/0.0.0)

**Released**: 2019.11.13

**Summary**:

*   Initial release!

# FortiGate Autoscale with AWS Transit Gateway Integration

## Project archive notice
**This project has been archived.** it is recommended to use the most current version of the **Amazon AWS** auto scaling deployment, located in the project [FortiGate Autoscale for AWS](https://github.com/fortinet/fortigate-autoscale-aws). This project supports any combination of Bring Your Own License (BYOL) and On-Demand instances as well as the option for Transit Gateway integration.

## Introduction
FortiGate Autoscale is collection of **Node.js** modules and cloud-specific templates which support auto scaling functionality for groups of FortiGate-VM instances on various cloud platforms.

AWS Transit Gateway can be used to connect Amazon Virtual Private Clouds (VPCs) and their on-premises networks to a single gateway. FortiGate Autoscale with Transit Gateway integration extends the protection to all networks connected to the Transit Gateway.

This project contains the code and templates for the deployment of FortiGate Autoscale on AWS with Transit Gateway integration. For deployment on other cloud platforms, visit the relevant repository:
* The **AliCloud** deployment is in the  [alicloud-autoscale](https://github.com/fortinet/alicloud-autoscale/) repository.
* The **Microsoft Azure** deployment is in the [fortigate-autoscale](https://github.com/fortinet/fortigate-autoscale) repository.
*  The **GCP** deployment is in the [fortigate-autoscale-gcp](https://github.com/fortinet/fortigate-autoscale-gcp) repository.

## Supported Platforms
This project supports auto scaling for the **Amazon AWS** cloud platform.

## Deployment Packages
To generate local deployment packages:

  1. Clone this project.
  2. Run `npm run build-aws-cloudformation` at the project root directory.

The deployment package as well as source code will be available in the **dist** directory.

| Package Name                               | Description                                                                                       |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| fortigate-autoscale-aws-cloudformation.zip | Cloud Formation template and related assets. Use this to deploy the solution on the AWS platform. |

## Deployment guide
A PDF is available: [deploying-auto-scaling-on-aws-tgw-1.1.7.pdf](./docs/deploying-auto-scaling-on-aws-tgw-1.1.7.pdf)


# Support
Fortinet-provided scripts in this and other GitHub projects do not fall under the regular Fortinet technical support scope and are not supported by FortiCare Support Services.
For direct issues, please refer to the [Issues](https://github.com/fortinet/fortigate-autoscale-aws-tgw/issues) tab of this GitHub project.
For other questions related to this project, contact [github@fortinet.com](mailto:github@fortinet.com).

## License
[License](./LICENSE) © Fortinet Technologies. All rights reserved.

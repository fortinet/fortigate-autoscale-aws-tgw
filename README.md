# FortiGate Autoscale with AWS Transit Gateway Integration

FortiGate Autoscale is collection of **Node.js** modules and cloud-specific templates which support autoscale functionality for groups of FortiGate-VM instances on various cloud platforms.

AWS Transit Gateway can be used to connect Amazon Virtual Private Clouds (VPCs) and their on-premises networks to a single gateway. FortiGate Autoscale with Transit Gateway integration extends the protection to all networks connected to the Transit Gateway.

This project contains the code and templates for the deployment of FortiGate Autoscale on AWS with Transit Gateway integration.

For autoscale on Azure and on AWS without Transit Gateway integration, see the main [fortigate-autoscale](https://github.com/fortinet/fortigate-autoscale/) repository. For autoscale on AliCloud see the [alicloud-autoscale](https://github.com/fortinet/alicloud-autoscale/) repository.

## Supported Platforms
This project supports autoscale for the cloud platform listed below.

  * Amazon AWS

## Deployment Packages
To generate local deployment packages:

  1. Clone this project.
  2. Run `npm run build-aws-cloudformation` at the project root directory.

The deployment package as well as source code will be available in the **dist** directory.

| Package Name | Description |
| ------ | ------ |
| fortigate-autoscale-aws-cloudformation.zip | Cloud Formation template and related assets. Use this to deploy the solution on the AWS platform.|

An Installation Guide is available from the Fortinet Document Library:

  * [FortiGate / FortiOS Deploying Auto Scaling on AWS with Transit Gateway integration](https://docs.fortinet.com/vm/aws/fortigate/6.2/aws-cookbook/6.2.0/397979/deploying-auto-scaling-on-aws)

## Deploy to AWS

<a href="https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/quickcreate?templateUrl=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Ffortinet-github-aws-release-artifacts%2Ffortigate-autoscale-aws-tgw%2Fmaster%2Ffortigate-autoscale-aws-cloudformation%2Ftemplates%2Fworkload-master.template&param_S3BucketName=fortinet-github-aws-release-artifacts&param_S3KeyPrefix=fortigate-autoscale-aws-tgw%2Fmaster%2Ffortigate-autoscale-aws-cloudformation%2F&stackName=fortigate-autoscale-tgw-demo&param_ResourceTagPrefix=fortigate-autoscale-tgw-demo" alt="Launch Stack" src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>

# Support
Fortinet-provided scripts in this and other GitHub projects do not fall under the regular Fortinet technical support scope and are not supported by FortiCare Support Services.
For direct issues, please refer to the [Issues](https://github.com/fortinet/fortigate-autoscale-aws-tgw/issues) tab of this GitHub project.
For other questions related to this project, contact [github@fortinet.com](mailto:github@fortinet.com).

## License
[License](https://github.com/fortinet/fortigate-autoscale-aws-tgw/blob/master/LICENSE) © Fortinet Technologies. All rights reserved.

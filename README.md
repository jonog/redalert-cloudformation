## Redalert CloudFormation

CloudFormation templates for [Redalert](https://github.com/jonog/redalert):

### redalert.yml

Pre-requisites:
* Remotely hosted configuration file

Stack includes:
* EC2
* ELB

### redalert-s3.yml

Pre-requisites:
* S3 bucket with configuration file

Stack includes:
* EC2
* ELB
* IAM role for access to S3 bucket config file

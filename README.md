# AWS_docs
## AWS

- [Tech Preview 2023](MSBA_Tech_Preview_2023.pdf)
- [Tech Preview: Launch an EC2 Instance](Launch_an_EC2_Instance.pdf)
- [Tech Preview: Where to get AWS Academy Lab Credentials](where_to_get_awsacademylab_credentials.pdf)
- [Tech Preview: How to create a S3 Bucket](create_an_S3_bucket.pdf)
- [Tech Preview: How can a student join an AWS Academy Course](How-can-a-student-join-a-course-at-AWS-Academy.pdf)
- Tech Preview: Create Uuntu EC2 Instance and Install Software [View Online](createUbuntuAndInstallSoftware.md) or [PDF](create_ubuntu_ec2_and_install_software.pdf)
- [AWS Academy Environment Restrictions](awsAcademyRestrictions.md)
- [Connect to S3](s3/README.md)
- MySQL on AWS 
  - [Create a MySQL Instance](rds/README.md#create-a-mysql-instance)
  - [Modify Security Inbound Rule to Allow Connections](rds/README.md#modify-security-group-inbound-rule)
  - [Troubleshooting RDS on AWS](rds/troubleShoot.md#troubleshooting)
- Redshift on AWS
  - [Create a Redshift Cluster](redshift/README.md#create-a-new-redshift-cluster)
  - [Modify Security Group Inbound Rules to Allow Connection](redshift/README.md#modify-security-group-inbound-rules)
- [Amazon EMR](EMR/README.md)  ```release emr-6.14.0```
  - [Launch a Spark EMR Cluster](EMR/README.md#launch-an-amazon-emr-cluster)
  - [Submit jobs to Running EMR Cluster](EMR/README.md#submit-work-to-amazon-emr)
  - [Modify Inbound Rules to Authorize SSH connections to your cluster](EMR/emrInboundRules.md)
  - [Connect to Running EMR Cluster Using SSH](EMR/README.md#connect-to-your-running-amazon-emr-cluster)
  - View web interfaces hosted on Amazon EMR clusters by Proxying
    - Using dynamic port forwarding
      - [Set up an SSH tunnel to the primary node](EMR/dynamicPortForwarding.md#set-up-an-ssh-tunnel-to-the-primary-node-using-dynamic-port-forwarding)
      - [Install and configure FoxyProxy using Mozilla Firefox](EMR/dynamicPortForwarding.md#install-and-configure-foxyproxy-using-mozilla-firefox)
      - [Install and configure SwitchyOmega using Google Chrome](EMR/dynamicPortForwarding.md#install-and-configure-switchyomega-using-google-chrome)
      - [URLs to access web interfaces in the browser](EMR/dynamicPortForwarding.md#access-a-web-interface-in-the-browser)
    - Using local port forwarding
      - [Set up an SSH tunnel to the primary node](EMR/localPortForward.md#local-port-forwarding)
      - [Run python scripts to access web interfaces hosted on Amazon EMR clusters for Windows/MacOS](scripts/README.md)
- [Create an Amazon EC2 Linux instance](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html)
- [Connect to your Amazon EC2 Linux instance](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstances.html)
- [Create an Amazon EC2 Windows instance](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/EC2_GetStarted.html)
- [Connect to your Amazon EC2 Windows instance](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/EC2_GetStarted.html#ec2-connect-to-instance-windows)
- [Connect to your Linux instance using an SSH client](connectToLinuxEC2UsingSSHClient.md)
- [Connect to your Linux instance using Putty](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/putty.html)
- [AWS S3 CLI Commands](https://docs.aws.amazon.com/cli/latest/userguide/cli-services-s3-commands.html)
- [Convert PEM to PPK File](pemAndPpkConversion.md)

### Emory University Netblock IPs
```shell
170.140.0.0/16
```

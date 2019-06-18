# Quick Start Guide: Installing Conduit on Amazon Web Service (AWS)

This guide assumes experience configuring AWS EC2 instances. For support, contact our Conduit support via email at support@bpcs.com to schedule time for one of our architects to assist in the deployment.

**Prerequisites**
1. You have an EC2 instance available within AWS. For instructions on creating an EC2 instance, check out [this article](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html). At a minimum, the EC2 instance needs to meet the following minimum requirements:
  * 4 cores
  * 16GB of RAM
  * Ubuntu Linux 16.04 LTS
2. Authorize inbound traffic for ports 80, 443 and 10002. For instructions on authorizing inbound traffic, check out [this article](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/authorizing-access-to-an-instance.html). You can limit access to the IP's that will access Conduit.

## Installation
1. Upload the Conduit .tar file and shell script to a folder on the EC2 instance.

2. Run the deployment script as root ./conduit-transformless-install.sh

3. When prompted, enter a name, email and password for the initial Conduit administrator account.

4. When prompted, enter the fully qualified domain name (FQDN) for the EC2 instance. Example: ec2-74-728-49-824.us-west-2.compute.amazonaws.com.

5. Once the script completes, open a web browser and navigate to the FQDN entered in Step 4.

6. Login with the administrator credentials you entered in Step 3.
![](https://www.dropbox.com/s/q8wfqqrpasut4qn/Screen%20Shot%202019-06-07%20at%209.26.48%20PM.png?raw=1)

## License Configuration

A valid license key, issued by Blueprint, is required in order to utilize Conduit.

1. In Conduit, go to the Settings (under global admin user's name)

2. Copy the generated License Token
![](https://www.dropbox.com/s/joee25ghtss33bk/Screen%20Shot%202019-06-16%20at%201.55.53%20AM.png?raw=1)

3. Email the license token to support@bpcs.com. You will receive your license key.

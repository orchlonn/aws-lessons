<!-- AWS Account root user -->
- IAM user is identitiy that reoresents a person application that interacts with AWS services and resources
<!--! BEST Practice -->
- Create a individual IAM users for each person who needs to access AWS.

<!-- IAM groups -->
- An IAM group is a collection of IAM users
- Members inherit the policies assigned to the group
<!--! BEST Practice -->
Attach IAM policiesto IAM groups, rather thatn to individual IAM users.

<!-- IAM policies -->
- An IAM policy is a document that grants or denies perms AWS services and resources. Also policy should be JSON.
<!--! BEST Practice -->
- Follow the security principle of leaset privileges.

<!-- AWS consolidated billing -->
A featur of AWS organizations allows you to receive a single bill for all AWS accounts in  your organization.

<!-- AWS security firewalls -->
AWS WAF helps protect your web applications or APIs against common web expoloits and bots that may affect availability, compromise security, or consume excesive resources. Also, AWS WAF can protect against Dos and DDoS attacks. 

<!-- Amazon cloud protection -->
1. AWS SHIELD -> AWS Shield provdies protection against distributed denial of service (DDoS) attacks.

<!-- Amaozn software vulnerability checks -->
Amazon inspector allows you to perform automated security assessment on your application. (S3 bucket is full internet access, thus Amazon inspector can help you with that.)

<!-- Encryption -->
At-Rest encryption --> This is the encryption of data that is stored on a device or in cloud service.
In-transit encryption --> This is the encryption of data as it travels from one place to another.

Also, we can upload encrypted file to the cloud service.

<!-- Amazon key management -->
AWS KMS (Amazon key management system) helps customers perform encryption operations through the use of cryptographic keys. You can choose the specific levels of access control that you need for your keys. 

<!-- Amazon intelligent threat detection -->
Amazon GuardDuty provides intelligent threat detection for AWS products and services. 




<!-- AWS storage types -->
There are three storage types:
1. Object Storage
2. Block Storage
3. File Storage

<!-- Block storage -->
* In block storage, files are seperated into equal-sized pieces (blocks) of data.
* Block storage is used for application that run on Amazon EC2 instance.

Instance store --> All data on the attached on the instance store is detected.

<!-- Amazon elastic block store -->
Amazon EBS is an easy-to-use, scalable, high-performance block storage service designed for EC2.

<!-- Amazon EBS volumes -->
If we lose or remove EC2 instance our EBS volume will be deleted.

<!-- Instance store -->
Tbere is real server provides instance store.

<!-- Amazon Elastic File System  -->
Amazon Elastic File System (AMAZON EFS) is a scalable file system used with AWS Cloud services and on-premises resources.

<!-- Comparing storage services -->
Amazon S3  vs Amazon EBS vs Amazon EFS

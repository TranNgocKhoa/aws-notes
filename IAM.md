**IAM User**
Access keys are long-term credentials for an IAM user or the AWS account root user. You can use access keys to sign programmatic requests to the AWS CLI or AWS API (directly or using the AWS SDK). Access keys consist of two parts: an access key ID (for example, AKIAIOSFODNN7EXAMPLE) and a secret access key (for example, wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY). As a user name and password, you must use both the access key ID and secret access key together to authenticate your requests. Access Keys are secret, just like a password. You should never share them.

**IAM Role** - An IAM role is similar to an IAM user, in that it is an AWS identity with permission policies that determine what the identity can and cannot do in AWS. However, instead of being uniquely associated with one person, a role is intended to be assumable by anyone who needs it.

**IAM Group** - An IAM group is a collection of IAM users. Groups let you specify permissions for multiple users, which can make it easier to manage the permissions for those users.

**AWS Policy** - You manage access in AWS by creating policies and attaching them to IAM identities (users, groups of users, or roles) or AWS resources. A policy is an object in AWS that, when associated with an identity or resource, defines their permissions.

**IAM access advisor**
Access advisor shows the service permissions granted to a user and when those services were last accessed. **You can use this information to revise your policies**. To summarize, you can identify unnecessary permissions so that you can revise your IAM policies accordingly.

**IAM credentials report** - You can generate and download a credential report that lists all users in your account and the status of their various credentials, including passwords, access keys, and MFA devices. It is not used to review permissions granted to a user.
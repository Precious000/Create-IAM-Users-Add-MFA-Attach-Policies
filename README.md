# Create-IAM-Users-Add-MFA-Attach-Policies
This Project will include the process of creating an IAM User, describe how you can add MFA, and attach Policies.
In AWS IAM are simply resources in IAM(Identity and Access Management) with permissions associated to the users account.


Follow the Steps Below to create an IAM User

.Log into your AWS account

Search for IAM service on the Console

click the option "Users" on the left Dashboard

Add a User or as many Users as you would want

Create a Group and add Permissions to the Group, Users in this group will inherit the Permissions in this group

Download the Credentials Presented on your screen!

That's it! You have your AWS IAM Users created.

#Best Practices in Creating IAM Users


it's Important to group Users, such that a number of Users can inherit Policies and Permisssions attached to a group. This way you can centrally manage all Users in a group.

Another best Practice is to add MFA to evry User accounts.

#How to Add MFA
Manually sellect a User
Sellect Security credentials
click on manage MFA(a QR code will apper)
Get your authenticator app on your mobile and Scan the QR Code
input the codes and there you have it.
MFA set for your Usesrs!

#Best Practice in Adding MFA

Add MFA to privilege Users and all accounts
Always Screenshot your QR Codes 



# awsdo
A python script to perform a Jumpcloud sso login and issue aws cli commands.

## example
```
awsdo --profile sso s3api list-buckets
```

## Sample .aws/credentials
```
[default]
output = json
region = us-west-2
account = saml2/aws-mine
username = my jumpcloud user name
password = my jumpcloud password

[production]
output = json
region = us-west-2
account = saml2/aws-production
username = my jumpcloud user name
password = my jumpcloud password

[development]
output = json
region = us-west-2
account = saml2/aws-development
username = my jumpcloud user name
password = my jumpcloud password
```

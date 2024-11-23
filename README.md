# aws
documentation

# cdk
**References**
**versions**: https://docs.aws.amazon.com/cdk/api/versions.html
 
**releases**: https://github.com/aws/aws-cdk/releases
 
**template, cdk version:**
https://docs.aws.amazon.com/cdk/v2/guide/bootstrapping-env.html

**Commands**
**Get bootstrap version**
aws ssm get-parameter --name /cdk-bootstrap/hnb659fds/version --query Parameter.Value

**Install aws-cdk**
npm install -g aws-cdk

**Bootstrap command**
cdk bootstrap 'aws://account-number/region' --profile profile-name

Example: cdk bootstrap 'aws://123456789012/eu-central-1' --profile profile-balasiksha

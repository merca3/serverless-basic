# How to use
### Docker
Install docker 
[Mac](https://docs.docker.com/desktop/install/mac-install/), 
[Windows](https://docs.docker.com/desktop/install/windows-install/), 
[Linux](https://docs.docker.com/desktop/install/linux-install/) 

### AWS
Install [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

Then run
```
aws configure
```
AWS Access Key ID: fake_key_id

AWS Secret Access Key: fake_access_key

Default region name: eu-west-1

Default output format: json

### DynamoDb admin
To install the local table viewer/editor, run `npm install -g dynamodb-admin`

### Start project
You will need three terminals
1. `sls dynamodb start --seed=test -m`
2. Windows: `SET DYNAMO_ENDPOINT=http://localhost:8010&&dynamodb-admin` For Mac/Linux: `DYNAMO_ENDPOINT=http://localhost:8000 dynamodb-admin`
3. `sls offline`

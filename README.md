## Example Infrastructure for a S3 backed CloudFront Distribution


### Getting Started

**Requirments:**
- [AWS CLI](http://docs.aws.amazon.com/cli/latest/userguide/installing.html#install-bundle-other-os)
- [jq](https://stedolan.github.io/jq/)

**Configuration:**
To run commands for a specific environment you must create an AWS CLI IAM profile for the environment. For example, to create a profile for a staging environment, you can run `aws configure --profile staging`. Make sure you update your config.json with your profile name.


### Usage

**Create a stack:**
To create a stack run
`./bin/upsert your_env`

**Update a stack:**
To create a stack run
`./bin/upsert your_env`

**View available outputs:**
To view available outputs run
`./bin/outputs your_env`

**View output value:**
To view available outputs run
`./bin/outputs your_env my-output`

**Upload a test file:**
To upload a test file to your distribution run
`./bin/upload_test_file your_env`

### Getting Help
If you need help or have questions please open a pull request [here](https://github.com/bradly/xxx/issues/new).

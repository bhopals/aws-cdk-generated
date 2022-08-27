# Welcome to your CDK TypeScript project

This is a blank project for CDK development with TypeScript.

Project is generated using

```
cdk init app --language typescript
```

Refer for more details - https://docs.aws.amazon.com/cdk/v2/guide/work-with-cdk-typescript.html

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

- `cdk bootstrap` bootstrapin (init) the stack.

- `cdk synth` emits the synthesized CloudFormation template

- `cdk deploy` deploy this stack to your default AWS account/region

- `cdk destroy` remove the stack


To Delete bootstrap

`aws cloudformation delete-stack --stack-name CDKToolkit`

`aws s3 ls | grep cdktoolkit # copy the name`

`aws s3 rb --force s3://cdktoolkit-stagingbucket-abcdef # <replace the name here>`

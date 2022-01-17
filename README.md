# Welcome to your CDK TypeScript project!

You should explore the contents of this project. It demonstrates a CDK app with an instance of a stack (`CdkWorkshopStack`)
which contains an Amazon SQS queue that is subscribed to an Amazon SNS topic.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template

## My Learnings
### to create a new TypeScript CDK project
* `cdk init sample-app --language typescript` to create a new TypeScript CDK project
* To synthesize a CDK app, use the `cdk synth` command
* You can use the `cdk bootstrap` command to install the bootstrap stack into an environment
* Use  `cdk deploy` to deploy a CDK app
* We can speed up that deployment time with `cdk deploy --hotswap`

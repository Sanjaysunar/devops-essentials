# DevOps Essentials on AWS
"Continuous delivery is a [DevOps](https://aws.amazon.com/devops/) software development practice where code changes are automatically built, tested, and prepared for a release to production. It expands upon [continuous integration](https://aws.amazon.com/devops/continuous-integration/) by deploying all code changes to a testing environment and/or a production environment after the build stage. When continuous delivery is implemented properly, developers will always have a deployment-ready build artifact that has passed through a standardized test process." [Source](https://aws.amazon.com/devops/continuous-delivery/)

AWS CodePipeline (along with other AWS Developer Tools such as AWS CodeCommit, AWS CodeBuild, and AWS CodeDeploy) is a fully-managed service for orchestrating continuous delivery. 


# Launch Stack
To launch the first solution (i.e. a static website to S3), you'll need to specify a unique S3 bucket name for the website bucket that will be created along with a GitHub token. Review and ensure you've configured the [Prerequisites](https://github.com/stelligent/devops-essentials/wiki/Prerequisites) before launching the stack below.

[![Launch CFN stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/template?stackName=devops-essentials-static&templateURL=https://s3.amazonaws.com/www.devopsessentialsaws.com/samples/static/pipeline.yml) 

The CloudFormation template is available [here](https://s3.amazonaws.com/www.devopsessentialsaws.com/samples/static/pipeline.yml).



# Hockeystick Devops Exercise

Your task, should you choose to accept it, is to get Chilby onto AWS.

# Task

Chilby is the CEO's dog so it is important that this task be handled with the greatest with care to ensure his comfort. So we are going to need you to fork this repo and add one or more scripts to do the following:

1. Create an EC2 instance
2. Install docker, minikube, and kubectl
3. Use the above tools to deploy the docker image listed below and make it available on the internet

You can use whatever you need to write the scripts: Chef, Ansible, Terraform, etc.

After you have completed the exercise please shut down any resources you have created in AWS. You don't need to make the scripts do this.

## Hints

minikube will probably only run with the `none` driver on a micro instance.

# Additional Information

## Docker image

The docker image to deploy is `benoithco/chilby`. It is published on the public docker registry.

We have provided the source for you in the `container` directory. *You do not need to build or modify it.* It is just provided for your reference.

The docker image listens on port 80 by default but it can be customized using the same settings as the `nginx` image if necessary.

## Guidelines

The above task should take you at most 2 hours.

Everything should be created in the ca-central-1 region.

You can only access AWS free tier services. Note that this means that you will only be able to create t2 and t3 micro instance types.

Be careful about your usage, AWS does not put a hard limit on actions that do not fall within the free tier. We have applied a number of restrictions to make it easier to stay within the limits, but your ability to stay within budget it a part of the test. You are also of course not authorized to make usage of the account for purposes outside of the test.

## AWS Access

Before you begin the task verify that you have received an invite to access our AWS instance.

If you have any issues accessing the AWS or performing tasks on it please let your interviewer know immediately. It is recomended that you verify you have access before starting.

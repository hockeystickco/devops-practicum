# Hockeystick Devops Exercise

Your task today is to help us play some server wack-a-mole.

So in this scenario you have been given Sysadmin level access to an AWS account where a number of ec2 instances are created and allocated for the use of various developers. However very few developers work in the middle of the night so we want to turn off their machines when they aren't around.

# Task

Write an AWS lambda script that finds all of the ec2 instances that have a specific tag and turns them off at 5:01 pm EDT and turns them back on at 8:30 am EDT.

The tag you should use is `WackAMole` with the value set to your email address.

You will need to create your own ec2 instances to test the lambda function.

Submit your deployment package and SAM file when you are done then delete the function and any instances you may have created.

You should use the `lambda-sysadmin-ec2-wackamole` role for your lambda function.

# Additional Information

## Guidelines

The above task should take you at most 2 hours. So we don't recommend waiting a full day to actually test it.

Everything should be created in the ca-central-1 region.

You can only access AWS free tier services. Note that this means that you will only be able to create t2 and t3 micro instance types.

Be careful about your usage, AWS does not put a hard limit on actions that do not fall within the free tier. We have applied a number of restrictions to make it easier to stay within the limits, but your ability to stay within budget it a part of the test. You are also of course not authorized to make usage of the account for purposes outside of the test.

## AWS Access

Before you begin the task verify that you have received an invite to access our AWS instance.

If you have any issues accessing the AWS or performing tasks on it please let your interviewer know immediately. It is recomended that you verify you have access before starting.

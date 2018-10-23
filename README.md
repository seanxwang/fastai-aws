# fastai-aws
One click launch of fully built fastai image on AWS, with automated Jupyter and idle shutdown

## why
fastai is a great resource, it is also becoming a machine learning platform to conveniently access deep learning algorithms, for both learning and exploration. However, setting up a fastai environment could be challenging for many users. For those using AWS, I developed this fully automated method to set up a fully functioning fastai environment in AWS with one click. 

## how to use
Prerequisite: you need to have an AWS account, have a key pair ready, and have basic familarity with AWS console, particularly CloudFormation. 

You will launch a CloudFormation stack with provided template, replace key pair parameter with your own value. In a few minutes after instance complete initialization, you will be able to access Jupyter Notebook by going to "https:<instance IP or DNS>:9999.

You have a fully functional fastai instance, and you can browse to fastai directory to run provided notebooks.

## parameters
The default password to access notebook is "jupyter". You should change it after you log in.

In the future, you can update template, with a newly released fastai AMI, or your own. You can also migrate your AMI to other AWS regions.

## implementation details
please refer to seanxwang.com

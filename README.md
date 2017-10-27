# Software Development Infrastructure

This sets up a software development infrastructure in the default VPC for Amazon.
This includes a VPC for DEV, QA/Staging & Production.  It's multi-language and stack,
by which I mean as many languages and stacks that I work with.

## Setup for AWS
export AWS_ACCESS_KEY_ID='Your key goes here'
export AWS_SECRET_ACCESS_KEY='Your secret access key goes here'
export ANSIBLE_HOSTS=./inventory/ec2.py
ssh-add ./etc/YourPemFileHere

### Mac OSX setup
export PYTHONPATH=`brew --prefix`/lib/python2.7/site-packages:$PYTHONPATH

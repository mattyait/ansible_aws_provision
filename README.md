[![Build Status](https://travis-ci.org/mattyait/ansible_aws_provision.svg?branch=master)](https://travis-ci.org/mattyait/ansible_aws_provision)[![npm version](https://img.shields.io/npm/v/npm.svg?style=flat)](https://www.npmjs.com/package/ansible_aws_provision)

# ansible_aws_provision
Repository to provision the infrastructure on AWS using Ansible

# Playbook Roles
VPC
This role is use to create a VPC, Internet gateway, private and public subnets within the vpc as well as it will create a public route table attached to the internet gateway.

Ec2
This role is use to create a ec2 instance within a private subnet under VPC.

security-group
This role is use to create a security group within VPC.

Run the playbook

`ansible-playbook -i inventory playbook_provisioning.yml`

# Ansible Complete Stack Setup

## Flow of execution
- Login to AWS
- Create ec2 instance to run ansible playbook
- Install Ansible
- Install boto
- Setup ec3 role for ansible
- Fetch Source code form project Ansible for AWS
- Execute VPC playbook
- Playbook to launch ec2, elb, sec grp for vprofile
- Get into vprofile vpc
- Playbooks for vprofile stack setup
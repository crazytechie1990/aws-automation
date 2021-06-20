# VM Migration Using Ansible

VM Import/Export enables you to import virtual machine (VM) images from your existing virtualization environment to Amazon EC2, and then export them back. This enables you to migrate applications and workloads to Amazon EC2, copy your VM image catalog to Amazon EC2, or create a repository of VM images for backup and disaster recovery.

Following AWS documentation and performing step by step is fine initially to attain knowledge. But when it comes to repeating the same task that's where it become tedious.

Ansible automation can do anything to avoid boredum. This project has two playbooks , once for exporting your onsite VM and then to import that VM as an AMI in to AWS.
In addition I have pasted another playbook to launch an instance using the same AMI.

# Requirements
- Ansible Installed
- AWS CLI configured
- Read AWS guide for recommendations before running a VM export.

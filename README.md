AMI image creation
==================

Creating AWS EC2 AMI images using Ansible.

Usage
-----

   $ ansible-playbook -v -i inventory create-ami.yml --extra-vars "@application.yml"

The playbook itself is generic, application and VPC specific variables are located in `application.yml`.

`Role` specified in `application.yml` will be applied to the created EC2 instance.

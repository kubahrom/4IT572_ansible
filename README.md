# 4IT572_ansible

- Install git
  `sudo yum install git`

- Install ansible, boto, boto3
  `pip3 install ansible boto boto3`

- Download git repo
  `git clone https://github.com/kubahrom/4IT572_ansible.git`

- CD into ansible folder (optional)
- Create ansible-vault (create, edit, view)
  `ansible-vault create group_vars/all/aws.yml`

- vim
  quit ESC, :q!
  save and quit ESC :wq

- get AWS cli keys from sandbox
- change variables to access_key: , secret_key: , session_token:

- Deploy EC2
  `ansible-playbook ec2_deploy.yml --ask-vault-pass`

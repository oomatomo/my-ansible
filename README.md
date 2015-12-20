# おれおれAnsible
主に開発環境等を整えたらいいなと
[![Build Status](https://travis-ci.org/oomatomo/my-ansible.svg)](https://travis-ci.org/oomatomo/my-ansible)

# Usage

### os check
ansible all -i hosts -u vagrant -a "cat /etc/redhat-release" --ask-pass""
### Show task
ansible-playbook -i hosts centos.yml --list-tasks

### Done
ansible-playbook -i hosts centos.yml
ansible-playbook centos.yml

# おれおれAnsible
主に開発環境等を整えたらいいなと

# Usage

### os check
ansible all -i hosts -u vagrant -a "cat /etc/redhat-release" --ask-pass""
### Show task
ansible-playbook -i hosts centos.yml --list-tasks

### Done
ansible-playbook -i hosts centos.yml
ansible-playbook centos.yml

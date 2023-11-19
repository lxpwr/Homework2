Домашнее задание по Ansible
Создана ВМ в Vagrant
Изначально был написан playbook на Ansible в одном файле и протестирована его работа - nginx.yml
Были созданы роли Ansible командой ansible-galaxy init deploy_nginx
Заново пересоздана ВМ в Vagrant и запущен playbook командой: 
ansible-playbook nginx_r.yml
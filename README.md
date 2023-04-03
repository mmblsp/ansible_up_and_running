# ansible_up_and_running

Automating Configuration Managment and deployment the Easy Way. DMK Press, 2018, ISBN 978-5-97060-513-4

## Глава 3

### Примечание

В реализации отхожу от задумки автора и не использую динамическуую конфигурацию, так как Vagrant хорошо интегрирован с ansible. Добавление секции config.vm.provision "ansible" в Vagrantfile позволяет получить инвентори с нужными группами в каталоге .vagrant
chapter3/playbooks/.vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory

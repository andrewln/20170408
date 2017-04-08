# 20170408
## Pre-requisites
* Virtualbox
* Vagrant
* Vagrant box - ubuntu/trusty64
* Ansible

## Setup
* $ cd ./vagrant
* $ vagrant up
* On your browser, you should see it on: http://127.0.0.1:12313/

## Application Setup:
* Changes in application, can be done by issuing vagrant provision
* Application Dependencies: vagrant/ansible/playbook.yml under pre_tasks
* Configuration on how does the application startup: vagrant/ansible/tasks/startup.yml

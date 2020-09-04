# ansible-web-app-role-demo

This repository is to demonstrate how we can create Ansible role to deploy a very simple web application.

**Used following docker image to provison target host -->**
```docker run -it -d rakeshrhcss/ubuntu-ssh-enabled```


**Run following command to deploy the application on a Docker host -->**
```ansible-playbook site.yml -i inventory```

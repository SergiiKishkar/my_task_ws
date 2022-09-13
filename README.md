# my_task_ws

Use Roles

- https://galaxy.ansible.com/likg/csf
- https://galaxy.ansible.com/postka/ansible_collection_lemp

Use Playbooks

1. ansible_playbook_general.yml
  my_task_ws/Ansible/ansible_playbook_general.yml

- install and configure CSF/LFD (https://configserver.com/cp/csf.html)
- install Wordpress
      
      domain_name: wp.com
      app_name: wordpress
      php_fpm_sock: /run/php/php-fpm.sock

      sites_path: /var/www/http_host

     db_name: wordpress
     db_host: localhost
     db_username: wordpressuser
     db_password: wordpresspass

2. ansible_playbook.yml 
my_task_ws/Ansible/ansible_playbook.yml

- istall Nginx
- install PHP 8.1 FPM
- install MySQL
- configurated SSH


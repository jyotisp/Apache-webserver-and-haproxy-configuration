# Apache-webserver-and-haproxy-configuration

In this we have a web.yml ansible playbook which configures 
the apache webserver and haproxy.

Here the setup of reverse proxy is achieved.

So the configuration file of haproxy needs to be updated when it finds 
a new webserver configured behind the scene.
So here I have automated that process using Ansible.

Ansible will automatically configure the webserver and haproxy also it will
add the webserver info in the configuration file of haproxy

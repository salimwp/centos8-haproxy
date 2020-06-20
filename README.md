This repo contains an Ansible playbook to build of HAproxy 2.0.15 on CentOS 8. 

Instructions can be found from the INSTALL file found in the source code archive and
the haproxy config was derived from https://www.haproxy.com/blog/the-four-essential-sections-of-an-haproxy-configuration/

Edit ansible/hosts and ansible/roles/03_config/haproxy/files/haproxy.cfg to match your specs.
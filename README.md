# GerbrandsLaptop
Configuration for my laptop

Adds few initial apt repo's using http://docs.ansible.com/ansible/apt_repository_module.html and keys http://docs.ansible.com/ansible/apt_key_module.html

Afer reinstalling Ubuntu on Gerbrand's laptop, install some inital software using:
* Install ansible, latest version. See http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-apt-ubuntu
* Update /etc/ansible/hosts, add gerlaptops section
* Run ansible-playbook site.yml


# Gerbrand's ansible configuration

The main goal if this project is to avoid me from having to install lots of software and tweaking after reinstalling my laptop. I decided to use Ansible for that.

* Install ansible, latest version. See http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-apt-ubuntu
* Update /etc/ansible/hosts, add gerlaptops section
* Run ansible-playbook site.yml

# TODO
Amongst others

* Detect release automatically. Saves me from changing the project after each new release of ubuntu
* Install/update/tweak configuration. Probably using dconf
* Read https://blog.josephkahn.io/articles/ansible/ , found this after I started this project

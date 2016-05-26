# GerbrandsLaptop
Configuration for my laptop

Adds few initial apt repo's using http://docs.ansible.com/ansible/apt_repository_module.html and keys http://docs.ansible.com/ansible/apt_key_module.html

Afer reinstalling Ubuntu on Gerbrand's laptop, install some inital software using:
* Install ansible, latest version from source. See http://stackoverflow.com/questions/30605302/ansible-not-recognizing-deb-parameter-for-aptitude/30625755
* Run ansible-playbook gerlaptop.yml -K


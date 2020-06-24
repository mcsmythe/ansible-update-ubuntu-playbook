
A simple but effective playbook to update Debian/Ubuntu servers. After setting up a ssh-key based Ubuntu server 
(I use Digital Ocean) I run this playbook first to update my servers before running provision playbooks. This handy lil' playbook is great to run to keep all your Ubuntu servers updated.


Just clone the playbook and enter your hosts name and run:

ansible-playbook update.yml

Then your set. Enjoy.

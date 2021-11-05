# Ansible-Lessons
Hometasks EPAM Ansible course

## Lesson01

To check the lesson01 clone the repo:
```
git clone https://github.com/prankbox/ansible-lessons.git
cd ansible-lessions
```

Make sure the inventory file has the right hosts:
```
cat inventory/example.ini
```
If not, make changes.

To install `httpd` and open ports 80 and 443 using `firewalld` run the playbook:
```
ansible-playbook -i inventory/example.ini 01-playbook.yml
```

To uninstall `httpd` and disable `firewalld` pors 80 and 443 run the playbook:
```
ansible-playbook -i inventory/example.ini 02-playbook.yml
```

To make changes to `/etc/default/grub` file run the playbook:
```
ansible-playbook -i inventory/example.ini 03-playbook.yml
```

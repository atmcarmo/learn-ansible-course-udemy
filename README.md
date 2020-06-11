This is a solution for the Udemy course "Ansible for Absolute Beinnger - Hands On - DevOps": https://www.udemy.com/course/learn-ansible/

# Bad practices note
Some best practices were not applied here as this is a test project (as an example the `inventories.txt` files has the servers' passwords, which is a really bad practice)

# Inventory
3 servers were provisioned as shown during the course using CentOS 8 (in the course CentOS 7 is used, though).

If you want to run the playbook on your ansible controler agains your targets please update the `inventories.txt` file with the correct IP addresses.

# Solution
I decided not use use a simple playbook but using Ansible roles as well.

# Future work
In the future I will use Vagrant to provision the VMs.

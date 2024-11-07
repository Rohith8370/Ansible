### add user 
* sudo adduser devops
### give sudo permissions to user
* sudo -i
* sudo visudo
### move to devops 
* su devops
### Change the value of PasswordAuthentication to yes 
 * /etc/ssh/sshd_config.d/60-cloudimg-settings.conf

### restart sshd service
* sudo systemctl restart ssh.service

### Create a key pair
*  ssh-keygen

### Now copy the public key into node1 
* ssh-copy-id devops@<node-1-ip>
# ansible install 

* sudo apt update
* sudo apt install software-properties-common
* sudo add-apt-repository --yes --update ppa:ansible/ansible
* sudo apt install ansible -y

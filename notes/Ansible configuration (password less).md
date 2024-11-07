### add user 
'''
sudo adduser devops

'''
### give sudo permissions to user
'''
sudo -i
visudo
'''
### move to devops 
### Change the value of PasswordAuthentication to yes 
'''
in /etc/ssh/sshd_config.d/60-cloudimg-settings.conf
'''
### restart sshd service
'''
sudo systemctl restart ssh.service
'''

ansible install 

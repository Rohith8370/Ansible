1.  sudo apt update
    sudo apt install software-properties-common
    sudo add-apt-repository --yes --update ppa:ansible/ansible
    sudo apt install ansible -y

2. ansible --version

3. Ansible ping test
    
    * 3.1  vi hosts
    * 3.2  cat hosts
    * 3.3  ansible -k -i hosts -m ping all



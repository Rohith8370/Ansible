### Manual Steps

1. Install nginx
   '''
    sudo apt update
    sudo apt install nginx -y
   '''
2. Now webserver should be installed
   '''
   sudo systemctl status nginx

   '''
3. Now we can access the webserver over http
   '''
   http://publicip

   '''
4. Now lets download the website into /tmp
   '''

   cd /tmp
wget https://www.free-css.com/assets/files/free-css-templates/download/page295/antique-cafe.zip

   '''
5. Install unzip
   '''
   sudo apt install unzip -y

   '''
6. Now unzip the antique-cafe
   '''
   unzip antique-cafe.zip

   '''
7. Now lets copy the folder 2126_antique_cafe to /var/www/html/cafe/
   '''
   sudo mv 2126_antique_cafe/ /var/www/html/cafe
   
   '''
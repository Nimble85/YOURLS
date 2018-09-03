# YOURLS
 #Create folder, download and unpack code
 
  mkdir /var/www/yourls
  cd /var/www/yourls
    git clone https://github.com/YOURLS/YOURLS/archive/1.7.tar.gz
    tar -zxvf 1.7.tar.gz 
    mv YOURLS-1.7/ yourls
    
 #Create conf file Apache
    
   sudo nano /etc/apache2/sites-available/yourls.conf
   
   

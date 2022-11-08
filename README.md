# MaksymFedunets
================For Ubuntu==============

Installation comands:


    sudo apt update
    
    sudo apt install apache2
    
    sudo apt install git
    
    git clone https://github.com/m0rtyni/MaksymFedunets



Start


    sh ~/MaksymFedunets/apache.sh


Stop 


    sudo systemctl stop apache2



Change start page: /var/www/html/index.html

or

    echo "YOUR TEXT" > /var/www/html/index.html

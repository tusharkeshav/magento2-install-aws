# One Touch Magento(OTM)
One click to install magento remotely using ansible.

# Tested using:
 Ubuntu (remotely on aws)
 kali(local)
 Python 2.7,
 ansible 2.8.1
 
 
 # Installing ansible and python: 
 - sudo apt install python2 ansible
 
 # Procedure:
 - first configure(local) machine to connect remote machine
 - first clone repository
 - run magento.yml file (using ansible-playbook command)
 
 ## Instructions:
 - Php7.1 is used. You can use Php7.2(but need a lot of changing)
 - change the host in file (default is xxx)
 - change base-url by your url(line no. 159)
 - add own database and add your user(line no. 111) or if already created just comment those lines no. 111-114
 - you have to add your own credential, and other paramters check line no. 158-172
 - magento is installed in director /var/www/magento2/
 - if you are installing magento other than ubuntu, then you have to change owner permissions at line no. 180, according to your user where you wanted to install magento.
 
 > for query/problem ping me up.
 

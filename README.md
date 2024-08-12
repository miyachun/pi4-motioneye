Raspberry Pi Imager  

sudo apt update  
sudo apt upgrade -y  
python3 -m venv .venv  
source .venv/bin/activate  
sudo apt install python3-dev libcurl4-openssl-dev libssl-dev  
sudo apt install python3-pip  
sudo pip3 install 'https://github.com/motioneye-project/motioneye/archive/dev.tar.gz'  
sudo motioneye_init  


http://<YOUR-IP>:8765  
Login: admin  
Password: (empty)  

-相關-
https://www.raspberrypi.com/software/  
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html  
https://www.realvnc.com/en/connect/download/viewer/?lai_sr=0-4&lai_sl=l  
https://raspberrytips.com/install-motioneye-on-raspberry-pi/  


sudo apt update  
sudo apt upgrade  
sudo raspi-config  
ifconfig  
sudo reboot  

-Virtualenv-  
python -m venv myenv  
source myenv/bin/activate  

sudo apt install python3-dev libcurl4-openssl-dev libssl-dev  
sudo apt install python3-pip  
sudo pip3 install 'https://github.com/motioneye-project/motioneye/archive/dev.tar.gz' --break-system-packages    
sudo motioneye_init  


http://YOUR-IP:8765  
Login: admin  
Password: (empty)  

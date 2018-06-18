# For 4.10 and older 
```
sudo apt-get install build-essential git dkms
git clone -b 4.10-down https://github.com/smlinux/rtl8723de.git
sudo dkms add ./rtl8723de
sudo dkms install rtl8723de/5.1.1.8_21285.20171026_COEX20170111-1414
```
Reboot

 
# For kernel 4.11 and newer
```
sudo apt-get install build-essential git dkms
git clone https://github.com/smlinux/rtl8723de.git
sudo dkms add ./rtl8723de
sudo dkms install rtl8723de/5.1.1.8_21285.20171026_COEX20170111-1414
```
Reboot
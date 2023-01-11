>> It's really pissed me off so, I tried this
```txt
sudo apt update
sudo apt upgrade
sudo add-apt-repository universe
sudo apt update
sudo apt install exfat-fuse
sudo apt install exfat-utils
sudo apt install exfatprogs
sudo apt upgrade exfatprogs
reboot
```
```txt
sudo apt update && apt upgrade && add-apt-repository universe && apt update && apt install exfat-fuse && apt install exfat-utils && apt install exfatprogs && apt upgrade exfatprogs && reboot
```

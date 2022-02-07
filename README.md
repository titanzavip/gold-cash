# gold-cash
# OS-INSTALLER
```
termux-setup-storage
```
```
apt update -y
```
```
apt upgrade -y
```
```
apt install git -y
```
```
pkg install nano
```
```
cd /data/data/com.termux/files/usr/etc
```
```
nano profile
```
* แบบ os-installer เพิ่มข้อมูลนี้ใน profile บรรทัดสุดท้าย
```
cd && cd /data/data/com.termux/files/usr/etc/os-install
sh ubun.sh
```
```
cd
```
```
git clone https://github.com/mantvmass/os-installer
```
```
cd os-installer
```
```
sh build.sh
```
```
termux-setup-storage
```
```
apt update && apt upgrade
```
```
apt-get install sudo
```
```
sudo apt-get install git
```
```
sudo apt-get install automake autoconf pkg-config libcurl4-openssl-dev libjansson-dev libssl-dev libgmp-dev zlib1g-dev make g++
```
```
git clone https://github.com/tpruvot/cpuminer-multi
```
```
cd cpuminer-multi
```
```
ls
```
```
sudo ./build-linux-arm.sh
```
```
sudo ./cpuminer -a yescryptr16 -o stratum+tcp://stratum-eu.rplant.xyz:7057 -u GSbEEn8T5YE4RdXHAvEXb7XYZc39kkePgo
```

Zergpool
```
sudo ./cpuminer -a yescryptr16 -o stratum+tcp://yescryptR16.asia.mine.zergpool.com:6333 -u DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9 -p c=DOGE,mc=GOLD
```
DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9

-a yescryptR16 -o stratum+tcp://yescryptR16.asia.mine.zergpool.com:6333 -u DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9 -p c=DOGE,mc=GOLD

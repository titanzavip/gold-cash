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
git clone https://github.com/curvehashcoin/cpuminer-curvehash.git
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
sudo ./cpuminer -a yescryptR16 -o stratum+tcp://yescryptR16.asia.mine.zergpool.com:6333 -u DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9 -p c=DOGE,mc=GOLD,m=solo,ID=realme-1 -c=7
```
```
sudo ./cpuminer -a yescryptR32 -o stratum+tcp://yescryptR32.asia.mine.zergpool.com:6343 -u DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9 -p  c=DOGE,mc=DMS,ID=realme-1 -c=7
```
```
sudo ./cpuminer -a equihash -o stratum+tcp://equihash.asia.mine.zergpool.com:2142 -u DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9 -p  c=DOGE,mc=ZEN,ID=realme-1 -c 7
```




DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9

-a yescryptR16 -o stratum+tcp://yescryptR16.asia.mine.zergpool.com:6333 -u DRkNn7KAtpiRk2ySwtxKWHMHTLPndREFW9 -p c=DOGE,mc=GOLD

Happy mining & solo mining! )

Windous Wallet http://cur.lv/121tqa

Linuks Wallet http://cur.lv/121tqf

Linux Daemon http://cur.lv/121tqj

Set up a swapfile if your system has less than 1.5GB of memory:

fallocate -l 2G /swapfile

chown root:root /swapfile

chmod 0600 /swapfile

mkswap /swapfile

swapon /swapfile

If fallocate doesn’t work, you can use dd if=/dev/zero of=/swapfile bs=1024 count=1024288 instead.

Initialize swapfile automatically on boot

nano /etc/fstab

Add this at the bottom: /swapfile none swap sw 0 0

exit shortcuts

ctrl+х

y

enter


Install all required dependencies:

apt-get update && apt-get upgrade

apt-get install ntp unzip git build-essential libssl-dev libdb-dev

apt-get install libdb++-dev libboost-all-dev libqrencode-dev

aptitude install miniupnpc libminiupnpc-dev

Pull the source code from github, or upload it yourself:

apt-get install nano

nano /etc/fstab

Add this at the bottom: /swapfile none swap sw 0 0

Install all required dependencies:

apt-get update && apt-get upgrade

apt-get install ntp unzip git build-essential libssl-dev libdb-dev

apt-get install libdb++-dev libboost-all-dev libqrencode-dev

apt-get install aptitude

aptitude install miniupnpc libminiupnpc-dev


Pull the source code from github, or upload it yourself

git clone https://github.com/Asscoin/Asscoin.git

cd Asscoin/src

rm -rf leveldb

cd leveldb

chmod 0777 ./build_detect_platform

make libleveldb.a libmemenv.a

cd ..

make -f makefile.unix USE_UPNP=1 USE_QRCODE=1 USE_UPNP=1

strip asscoind

cp asscoind /usr/bin

cd ~

asscoind

oops! )))

cd .asscoin/asscoin.conf

Writes the data in the editor

rpcuser=your nickname

rpcpassword=your strong password

rpcport=8142

port=8141

addnode=162.222.227.106

listen=1

daemon=1

server=1

rpcallowip=127.0.0.1


exit shortcuts

ctrl+х

y

enter

asscoind

terminal response "Asscoin server starting"

Yes!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

ASS!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!


GOOD MINING!




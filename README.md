#TRERMUX

pkg upgrade

pkg update

pkg install git

pkg install python3

git clone ttps://github.com/ngochuyen2016/ddosvip.git

cd ddosvip

pip3 install -r requirements.txt

python3 ddos.py --proxy.txt

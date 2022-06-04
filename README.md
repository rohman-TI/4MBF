# 4MBF
pkg update && pkg upgrade

pkg install python git

pip install requests bs4 futures

pip install cython

rm -rf 4MBF

termux-setup-storage

git clone https://github.com/iyanxlord/4MBF

cd 4MBF

git pull

python 4MBF.py


rm -rf $HOME/obbtool

pkg update && pkg upgrade

pkg install git

termux-setup-storage

git clone https://github.com/zoulobb/obbtool.git

cd obbtool

chmod +x zoulobb

./zoulobb

以后使用直接输入 obb走了 就可以了
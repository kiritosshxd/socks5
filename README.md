#ROOT SENHA

source <(curl -sL 'https://raw.githubusercontent.com/kiritosshxd/socks5/refs/heads/main/root.sh')

#SOCKS5

wget -O socks5 https://github.com/kiritosshxd/socks5/raw/refs/heads/main/socks5

chmod 777 socks5

./socks5 -port 1080 -allow IP

#SOCKS5 INSTALL

source <(curl -sL 'https://raw.githubusercontent.com/kiritosshxd/socks5/refs/heads/main/socks5.sh')


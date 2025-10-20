#ROOT SENHA

source <(curl -sL 'https://www.dropbox.com/scl/fi/yw9ug58cxhulefw1v22sw/alterar.sh?rlkey=hklmtpyw68lb0dff79fopstjx')

#SOCKS5

wget -O socks5 https://github.com/kiritosshxd/socks5/raw/refs/heads/main/socks5

chmod 777 socks5

./socks5 -port 1080 -allow IP

#SOCKS5 ISNTALL

source <(curl -sL 'https://raw.githubusercontent.com/kiritosshxd/socks5/refs/heads/main/socks5.sh')


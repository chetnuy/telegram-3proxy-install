# telegram-3proxy-install
Bash script to install socks5 proxy (3proxy) configured for telegram.
Can be used on Debian/Ubuntu vps/vds with public ip (without NAT). Connections to non-telegram servers will be rejected.

Simply run the script with root privileges:
sudo ./install.sh

## todo

- [ ] добавить возможность автоматической настройки, если на хосте несколько IP адресов  
- [ ] добавить в конфиг настройки авторизации по IP  
- [ ] добавить настройки для протокола HTTP/S PROXY, параллельно с SOCKS5, соединение на разные порты для PROXY и SOCKS


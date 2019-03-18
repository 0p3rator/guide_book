# vpn

- v2ray
- cow


## v2ray
use to break GFW

install bash  
`bash <(curl -L -s https://install.direct/go.sh)`

check status v2ray  
`sudo systemctl status v2ray`

check port v2ray  
`netstat -ntlp | grep 1080`

open system setting and enter network proxy  
then select `mannual proxcy setting` add content below into `socks host` text area  
`127.0.0.1 port 1080`


## cow 
use to change socks protocol into http protocol

see at [here](https://github.com/cyfdecyf/cow)



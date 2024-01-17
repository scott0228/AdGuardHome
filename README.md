改密碼的方式：  
htpasswd -nbB admin 'MyNewPassword'   
再將密碼改到 conf/AdGuardHome.yaml 裡  


sudo iptables -I INPUT -p tcp -m tcp --dport 53 -j ACCEPT
sudo iptables -I INPUT -p udp -m udp --dport 53 -j ACCEPT

https://docs.cloudron.io/apps/adguard-home/

# KDE - Manual Bluetooth Tethering 

# Prerequisites
```
sudo apt-get install bluetooth ppp -qq
```

# Prepare Point to Point Protocol
```
sudo chmod +x /usr/sbin/pppd
sudo touch /etc/ppp/options
mkdir -p /etc/ppp/peers
echo nodetach noauth userpeerdns defaultroute > /etc/ppp/peers/securetether
```

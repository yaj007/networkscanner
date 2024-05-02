# Networkscanner

Networkscanner is LAN scanner in python 3

It can be used to scan a target or a network range

it works on ARP to scan network 

# Installation
sudo -i
git clone https://github.com/yeasin1052/cse496-networkscanner

cd cse496-networkscanner

cd Networkscanner

sudo chmod +x setup.sh

sudo bash setup.sh

networkscanner -t [target]

  
# Example

networkscanner -t 192.168.0.1

networkscanner -t 192.168.0.101

networkscanner -t 192.168.0.101/24

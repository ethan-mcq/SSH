# SSH
```
sudo apt install openssh-server
sudo systemctl status ssh
```
Should show 'Active'
```
sudo ufw allow ssh
sudo systemctl enable ssh
```
SSH should be running on the machine now

# IP address
```
ip address #note the ip address
```
Test on another machine connected to the same network by entering this into your terminal:
```
ssh username.of.host@IPADDRESS 
```
enter password for access!

# Port forwarding
This will be specific to the router. You will need to get into the router settings on a browser and you can port forward the IP that you got earlier. I'm not entirely apt at explaining/doing this step.

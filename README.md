VPS Script Smart Tunnel <br>
Owner FarhanAnsari @farhanansari_888<br>
<br>
simple installation <br>
<br>
just copy the command and run script<br>
<br>
first type this command to go in root<br> 
``` sudo su <br> ```
<br>
<br>

after reaching root directory run this command <br>
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/NETWORKTWEAKER/AUTO-SCRIPT/master/setup1.sh && chmod +x setup1.sh && sed -i -e 's/\r$//' setup1.sh && screen -S setup ./setup1.sh
```


now reboot your vps and all set

script: Smart Tunnel
Owner: FarhanAnsari <br>@farhanansari_888

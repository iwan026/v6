#🇮🇩 YUI VPN🇮🇩

* Tahap 1
```
apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && apt -y install xxd && apt install -y bzip2 && apt install -y wget && apt install -y curl && reboot
```
* Tahap 2
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/iwan026/v6/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

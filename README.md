## SUPPORT OPERATING SYSTEM
> Debian GNU/Linux 11 (Bullseye) -Not stable with this script-
>
> Debian GNU/Linux 10 (Buster)
>
> Debian GNU/Linux 9 (Stretch)
>
> Ubuntu Server 21.04 LTS (Hirsute Hippo)
>
> Ubuntu Server 20.04 LTS (Focal Fossa)
>
> Ubuntu Server 18.04 LTS (Bionic Beaver)





### SALIN DAN PASTE
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/CTechDidik/CtechDidikAutoScriptVPN/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

# tun2sock
tun2sock 


https://tachyondevel.medium.com/%E6%95%99%E7%A8%8B-%E5%9C%A8-windows-%E4%B8%8A%E4%BD%BF%E7%94%A8-tun2socks-%E8%BF%9B%E8%A1%8C%E5%85%A8%E5%B1%80%E4%BB%A3%E7%90%86-aa51869dd0d
```
http://build.openvpn.net/downloads/releases/tap-windows-9.22.1-I602.exe
https://github.com/eycorsican/go-tun2socks/releases/download/v1.11.2/tun2socks-windows-4.0-amd64.exe.zip
```
```
tun2socks-windows-4.0-amd64.exe -h

tun2socks-windows-4.0-amd64.exe -tunAddr 10.0.0.2 -tunGw 10.0.0.1 -proxyType socks -proxyServer ?.?.?.?:1086 -tunDns 8.8.8.8,8.8.4.4

tun2socks-windows-4.0-amd64.exe -tunAddr 10.0.0.2 -tunGw 10.0.0.1 -proxyType shadowsocks -proxyServer ?.?.?.?:1086 -dnsServer 8.8.8.8,8.8.4.4 -proxyCipher AES-256-CFB -proxyPassword 123456


```

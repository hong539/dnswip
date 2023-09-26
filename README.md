# dnswip
DNSWIP is a Domain Name Server Written In Python.

## guides

* UDP server
* [Make your Own DNS Server](https://www.youtube.com/playlist?list=PLBOh8f9FoHHhvO5e5HF_6mYvtZegobYX2)
    * [source codes](https://github.com/howCodeORG/howDNS)
* [rfc1035 DOMAIN NAMES - IMPLEMENTATION AND SPECIFICATION](https://www.ietf.org/rfc/rfc1035.txt)
    * Header section format
    * Message compression

## Quick start

```shell
#one terminal as server
sudo python main.py

#one terminal as client
dig howcode.org @127.0.0.1
```
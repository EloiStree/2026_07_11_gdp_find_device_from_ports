```
git submodule add https://github.com/EloiStree/2026_07_11_gdp_find_device_from_ports.git addons/2026_07_11_gdp_find_device_from_ports
```

# 2026_07_11_gdp_find_device_from_ports

> mDNS may fail on Quest 3 and some devices. In that case, use a fixed IP or discover devices by scanning ports and creating a digital fingerprint.
>
> 
During my last project using Quest 3 with a Raspberry Pi 5 as the server, I learned that mDNS cannot always be relied on. For example, it did not work properly with Quest 3 under Unity.

As a workaround, I used a Python script listening on a specific port. If a device has ports 8080 and NNNN accessible, it could be identified as our target device.

🚧 I’m creating this repository now to implement this discovery mechanism later. 🚧

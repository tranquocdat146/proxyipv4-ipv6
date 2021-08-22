Redirect connections from different ports at one ipv4 address to unique random ipv6 address from \64 subnetwork. Based on 3proxy

cover
Requirements

    Centos 8
    Ipv6 \64

Installation

VPS from Vultr 100$ free used as Centos setup

    bash <(curl -s "https://raw.githubusercontent.com/thuongtin/ipv4-ipv6-proxy/master/scripts/vultrcentos8.sh")

    After installation dowload the file proxy.zip
        File structure: IP4:PORT:LOGIN:PASS
        You can use this online util to change proxy format as you like

Test your proxy

Install FoxyProxy in Firefox Foxy

Open ipv6-test.com and check your connection check ip

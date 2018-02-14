# DNS Tunnel

Based on [VPN-over-DNS](https://www.vpnoverdns.com/perl.html)

### Install

    sudo cpan
    install Net::DNS
    exit

One Time Login:

    perl vpnoverdns.pl -i username password

Per Session ?

    export http_proxy=http://localhost:8080

### Run

    perl vpnoverdns.pl -L 8080:127.0.0.1:3128
    
In another terminal:

    lynx http://www.bbc.co.uk/news
    
#### Notes

lynx a light weight text based browser
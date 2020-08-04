# Ways to get public IP address

## DNS
```
dig +short @1.1.1.1 ch txt whoami.cloudflare | tr -d '"'
```
```
dig +short @ns1.google.com txt o-o.myaddr.l.google.com | tr -d '"'
```
```
dig +short myip.opendns.com @resolver1.opendns.com
```
```
dig +short whoami.akamai.net. @ns1-1.akamaitech.net
```


## Web service
### IP-only response
```
curl https://checkip.amazonaws.com/
```
```
curl https://ident.me/
```
```
curl https://api.ipify.org/
```
```
curl https://icanhazip.com/
```
```
curl https://ifconfig.co/
```
```
curl https://ifconfig.io/
```
```
curl https://ifconfig.me/
```
```
curl https://api.ip.sb/ip
```

### JSON response with GEO info
```
curl https://api.myip.com/
```
```
curl https://ifconfig.co/json
```

### API
> https://ipstack.com/

> https://www.ipify.org/

> https://developers.google.com/maps/documentation/geolocation/


## Utilities
> https://ping.pe/

> https://gsuite.tools/

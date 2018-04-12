# Authoritative Name Server `ns.HerCDN.com`

By default, `ns.herCDN.com` contains the following Resource Records:  
| Resource Record | Use |
| - | - |
| (herCDN.com, www.herCDN.com, CN) | Translates `herCDN.com` to `www.herCDN.com` |
| (www.herCDN.com, xxx.xxx.xxx.xxx, A) | IP for `www.herCDN.com` |  

## Compile and Run
To run
```
javac HerCDNNS.java
java HerCDNNS
```
Set following variables after running the program:
- **IP** for the web-server/machine running `www.herCDN.com`
- **PORT** for the name-server/machine running `ns.herCDN.com`

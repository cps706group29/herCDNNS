# Authoritative Name Server ns.HerCDN.com
Class `ResourceRecord` stores psuedo resource record objects.  

By default, `ns.herCDN.com` contains the following Resource Records:  
- (herCDN.com, www.herCDN.com, CN) : *Canonical resolve for herCDN.com*
- (www.herCDN.com, xxx.xxx.xxx.xxx, A) *IPv4 for www.herCDN.com*

## Set up
The following variables should be set:
- IP for web-server/machine running **ww.herCDN.com**
- Port for name-server/machine running *ns.hercdn.com*
Set the two lines accordingly:
```
public static final String HER_CDN_IP = "xxx.xxx.xxx.xxx";
public static final int HIS_CINEMA_NS_LISTENING_PORT = xxxxx;
```
## Run
To run
```
javac HerCDNNS.java
java HerCDNNS
```

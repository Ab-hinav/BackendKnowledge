# How DNS works and what is it ?
- DNS - domain name server , used to answer the question www.google.com -> which ip address to  send req to

## Journey of a Request from browser - https:://www.google.com
- Browser first checks in its cache , then check with OS in its cache
- Then OS calls resolver(Ip provider) .
- The resolver checks in its cache , if not then it send req to TLD server (top level domain)
- TLD or root , root level server -> .com level server 
- .com level ->authoritative server -> final ip
- all this is done while caching in the way for future needs

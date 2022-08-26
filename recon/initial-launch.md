This repo include the methods to find subdomains and open ports

> 1. Most commond ports to scan with httpx and naabu
```
81,300,591,593,832,981,1010,1311,1099,2082,2095,2096,2480,3000,3128,3333,4243,4567,4711,4712,4993,5000,5104,5108,5280,5281,5601,5800,6543,7000,7001,7396,7474,8000,8001,8008,8014,8042,8060,8069,8080,8081,8083,8088,8090,8091,8095,8118,8123,8172,8181,8222,8243,8280,8281,8333,8337,8443,8500,8834,8880,8888,8983,9000,9001,9043,9060,9080,9090,9091,9200,9443,9502,9800,9981,10000,10250,11371,12443,15672,16080,17778,18091,18092,20720,32000,55440,55672
```
```
For httpx scan you can directly use the above ports but for naabu you can save all the ports in a file called common-ports.txt and then type the following command
```
naabu -l live-httpx-target.txt -pf common-ports.txt -ep 80,443 -c 200 -timeout 1500
```
cat visma.txt | httpx -p 81,300,591,593,832,981,1010,1311,1099,2082,2095,2096,2480,3000,3128,3333,4243,4567,4711,4712,4993,5000,5104,5108,5280,5281,5601,5800,6543,7000,7001,7396,7474,8000,8001,8008,8014,8042,8060,8069,8080,8081,8083,8088,8090,8091,8095,8118,8123,8172,8181,8222,8243,8280,8281,8333,8337,8443,8500,8834,8880,8888,8983,9000,9001,9043,9060,9080,9090,9091,9200,9443,9502,9800,9981,10000,10250,11371,12443,15672,16080,17778,18091,18092,20720,32000,55440,55672,80,443 -o visma-live.txt
```
> Find all jira subdomains of a target
```
Get Jira subdomains for your targets 🔥🔥🔥🔥
Use these Google dorks 🔥🔥

inurl:<COMPANY_NAME> intitle:JIRA
inurl:<COMPANY_NAME> intitle:JIRA
site:*.<HOSTNAME>.com filetype:jspa
site:*.<HOSTNAME>.com ext:jspa
```
> Check AWS S3 instances for read/write/delete access
```
https://github.com/0xmoot/s3sec
```
> Port Scanner
```
https://github.com/s0md3v/Smap
```
> Useful tools
```
https://github.com/edoardottt/lit-bb-hack-tools/tree/main/eae
https://github.com/edoardottt/lit-bb-hack-tools/tree/main/eefjsf
https://github.com/edoardottt/lit-bb-hack-tools/tree/main/rapwp
```
>An unconventional Windows reverse shell, currently undetected by Microsoft Defender and various other AV solutions, solely based on http(s) traffic.
```
https://github.com/t3l3machus/hoaxshell
```

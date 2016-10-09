---
layout: post
title: 小于500，除以7余1且除以3余2的数有多少个？
---

假设满足条件的数为N，则有N=7k+1 （k=0,1,2,3...），且N<500  
故N=7k+1<500 => k<72  
又有N除以3余2，所以**N+1可以被3整除**  
下面使用列举法，找出被3整除的数  
列举N+1=7k+2 (k=0,1,2,...,71)

| k | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| N+1 | **9** | 16 | 23 | **30** | 37 | 44 | **51** | 58 | 65 | **72** |

| k | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | ... |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| N+1 | 78 | 95 | **102** | ... | ... | ... | ... | ... | ... | ... | ... |

观察上表**加粗部分**可知，从k=1开始，每增加3，N+1就可以被3整除，根据等差数列性质容易求得这样的数有24个。
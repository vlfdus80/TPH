## 사용법
> ./transactions_per_hour_v1.0.sh 파일명

```bash
test@ykd2:~/gitwork_hour$ ./transactions_per_hour_v1.0.sh accesslog/access.202209230000


Total Line Count : 1400012

******************Group by Method*****************
GET Methon Count : 699428

POST Method Count : 699979

OPTION Method Count : 298

HEAD Method Count : 306

ETC Count : 1

Method Total Count : 1400012

GET AND POST Method to Test Count : 1399407

OK
**********Group by Dynamic & Statuc***************
Static pages in GETPOST Count : 315313

Dynamic pages in GETPOST Count : 1084094

OK
*********transaction count per hour***************
Dynamic pages in GET AND POST
00 : 17197
01 : 19255
02 : 12254
03 : 14076
04 : 12521
05 : 14124
06 : 8975
07 : 11113
08 : 38845
09 : 73826
10 : 104598
11 : 81652
12 : 45088
13 : 70531
14 : 74851
15 : 101680
16 : 94884
17 : 93373
18 : 60396
19 : 35237
20 : 27941
21 : 25783
22 : 24146
23 : 21748
SUM : 1084094

OK
```

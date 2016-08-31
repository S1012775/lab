# lab

1. 電影網 <br>
 https://web-annyke.c9users.io/EasyMVC/EasyMVC/Home/index

2.簡易銀行系統 <br>
https://payment-annyke.c9users.io/bankSystem/Home/index

3.活動報名系統 <br>
https://booking-annyke.c9users.io/EasyMVC/Home/select

4.API<br>
https://payment-annyke.c9users.io/Api/api.php

新增帳號

api名稱 - addUser

參數1 - user(帳號)

https://payment-annyke.c9users.io/Api/api.php/addUser?user=Anny

取得餘額

api名稱 - getBalance

參數1 - (string)user(帳號)

https://payment-annyke.c9users.io/Api/api.php/getBalance?user=Anny

轉帳

api名稱 - Transfer

參數1 - (string)user(帳號)

參數2 - (string)type(轉帳型態) (IN,OUT)

參數3 - (int)transid(轉帳序號)

參數4 - (int)amount(轉帳金額)

https://payment-annyke.c9users.io/Api/api.php/Transfer?user=Anny&type=OUT&transid=006&amount=500

檢查轉帳狀態

api名稱 - transferCheck

參數1 - (string)user(帳號)

參數2 - (int)transid(轉帳序號)

https://payment-annyke.c9users.io/Api/api.php/transferCheck?user=Anny&transid=006

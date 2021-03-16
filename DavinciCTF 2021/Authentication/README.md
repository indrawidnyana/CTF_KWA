# Authentication - 10 points
## Description

![2 soal](https://user-images.githubusercontent.com/54881761/111333643-75434200-86a5-11eb-9931-431e2399d968.JPG)

## Flag

> dvCTF{!th4t_w4s_34sy!}

## Solution

> Melakukan Login dengan SQL Inject dengan syntax **SELECT * FROM Users WHERE Username='$username' AND Password='$password'** 

![2 1 login dengan standar payload admin](https://user-images.githubusercontent.com/54881761/111334161-e84cb880-86a5-11eb-8509-d9851358a086.JPG)

> Lalu setelah berhasil masuk lakukan inspect element pada halaman website

![2 2 melakukan inspect element](https://user-images.githubusercontent.com/54881761/111334180-eaaf1280-86a5-11eb-98e9-3da97b352f0e.JPG)

> Selanjutnya flag dapat ditemukan dibagian bawah hasil inspect element website.

![2 3 mendapatkan flag](https://user-images.githubusercontent.com/54881761/111334190-ed116c80-86a5-11eb-977a-d33aae9a0cf9.JPG)

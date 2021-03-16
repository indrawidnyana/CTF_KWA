# Authentication - 10 points
## Description

Can you find a way to authenticate as admin?

http://challs.dvc.tf:1337/

## Flag
```
dvCTF{!th4t_w4s_34sy!}
```
## Solution
Menggunakan SQL Inject. Untuk melewati halaman login mengketikkan ```SELECT * FROM Users WHERE Username='$username' AND Password='$password'``` lalu didalam db tersebut terdapat flag
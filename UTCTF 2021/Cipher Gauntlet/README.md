# Cipher Gauntlet - 100 points
## Description

Can you make it through all of the encodings and ciphers?
Hint : Make sure whatever tool you use doesn't remove underscores and curly brackets since they're in the final flag!

## Flag
```
utflag{now_youre_playing_with_crypto}
```
## Solution
Download file ```secret.txt``` yang berisi bilangan biner, lalu bilangan biner tersebut dijadikan plaintext, setelah jadi plaintext, decode enkripsi dengan base64, setelah di decode, hasil decode dijadikan caesar cipher. Lalu didapatkan flag tersebut
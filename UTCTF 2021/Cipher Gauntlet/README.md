# Cipher Gauntlet - 100 points
## Description

![2 soal](https://user-images.githubusercontent.com/54881761/111335722-31513c80-86a7-11eb-8112-7a06c63a3de9.JPG)

## Flag

> utflag{now_youre_playing_with_crypto}

## Solution

* Melakukan encode pada binary yang didapatkan dengan binary encoder

![2 1 cipher gauntlet, melakukan encode pada binary](https://user-images.githubusercontent.com/54881761/111335733-33b39680-86a7-11eb-8fe7-8b0da65a8e84.JPG)

* Melakukan cipher analysis pada clue yang di dapatkan pada proses sebelumnya dan mendapatkan hasil cipher yaitu **Base64**

![2 2 melakukan analysis pada next clue dan dapat hasil base64 cipher](https://user-images.githubusercontent.com/54881761/111335741-3615f080-86a7-11eb-9cfc-1c99d48a86e7.JPG)

* Melakukan decode pada cipher clue sebeluumnya dengan **Base64** Cipher

![2 3 melakukan decode pada base64 sesuai clue](https://user-images.githubusercontent.com/54881761/111335745-36ae8700-86a7-11eb-84a0-848f2c252c93.JPG)

* Mendapatkan clue baru dari proses decode sebelumnya

![2 4 mendapatkan clue](https://user-images.githubusercontent.com/54881761/111335749-37471d80-86a7-11eb-8588-ecfd247b9fb9.JPG)

* selanjutnya kembali melakukan analysis terhadap clue yang didapatkan dan mendapatkan hasil analysis **Caesar Cipher**

![2 5 melakukan analysis dan ternyata bentuknya adalah caecas](https://user-images.githubusercontent.com/54881761/111335752-37dfb400-86a7-11eb-8937-02915a6c6f5b.JPG)

* Lalu kembali melakukan decode pada clue sebelumnya dengan metode **Caesar Cipher**

![2 6 melakukan decode pada clue selanjutnya](https://user-images.githubusercontent.com/54881761/111335757-38784a80-86a7-11eb-8721-d3a0652aa857.JPG)

* Setelah di decode maka flag akan ditemukan

![2 7 mendapatkan hasil flag](https://user-images.githubusercontent.com/54881761/111335760-3910e100-86a7-11eb-9211-63563befbe3f.JPG)

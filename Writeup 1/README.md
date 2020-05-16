# Writeup 1

> ### About Challenge

This challenge was about an image. The file provided is available [here](/Writeup%201/earth.png). When you try to open given .PNG with any photo viewer app, it shows an error.

> ### Solution

* This happens when either .PNG is not a suitable extension for the file, or something is wrong at the Hex level of the file.
* Firstly we will analyze the Hex of the file. For this purpose, you can use [Hexed.it](http://hexed.it).
* <img src=../Writeup%201/hex.jpg>
* we can see that file signature is @NG instead of PNG. Replace @ with P and export newly created file.Open It.

You will find the Flag.
<img src=../Writeup%201/earth%20(2).png>
> Flag is `JCTF{Y0u_ch4NG3_THE_f1L3_sign4tur3??}`
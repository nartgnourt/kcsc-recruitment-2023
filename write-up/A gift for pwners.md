# A gift for pwners

![A gift for pwners](images/A-gift-for-pwners.png)

Tải xuống file gift và em đã thử command `strings gift | grep -i kcsc` thì lấy được 1 phần của `flag`.
![flag-1](images/gift-flag-1.png)

Thử tiếp command `strings gift | grep '}'` thì đã lấy được phần cuối của `flag`.
![flag-3](images/gift-flag-3.png)

Em ghép 2 phần `flag` lại thì thấy thiếu thiếu. Nhớ đến tên challenge là "A gift for pwners" nên em dùng command `strings gift | grep -i 'for'` lấy được phần ở giữa.
![flag-2](images/gift-flag-2.png)

## Flag
`KCSC{A_gift_for_the_pwners_0xdeadbeef}`




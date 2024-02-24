# **Babyrev_level4.1**

Như level trước mình cũng chạy thử chương trình nhưng không thấy có gợi ý gì nên mình mở bằng `IDA` để kiểm tra xem có gì hay ho trong đó không.

Khi kiểm tra qua đôi chút mình phát hiện ra một chuỗi `dhkpu` khá đáng chú ý, và 1 đoạn code xử lý input mình nhập.

![r4 1 1](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/1e3a5c5a-07e6-46fe-85c3-ea1fee29088c)

![r4 1 2](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/5a616748-a0ec-4f0d-a602-f004f334a053)


Đoạn code trên có logic khá rối và mình nghĩ tới việc thử nhập chuỗi mình tìm được bên trên trước rồi tính.

Và sau đó mình nhận được flag luôn mà chưa cần tới đoạn code kia.

![r4 1 3](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/603ed6d6-eb75-4870-8b96-f56865121c0e)

> **Flag: pwn.college{IPqvzAMOznAMF2WqnICUjN7ljw0.0FO1IDL3gDN3QzW}**

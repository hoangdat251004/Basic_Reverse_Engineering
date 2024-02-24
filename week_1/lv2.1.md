# **Babyrev_level2.1**

Tại level này mình nghĩ chắc nó cũng thay đổi vị trí ký tự của input mình nhập nên mình mở chương trình bằng `IDA` để tìm thêm thông tin.

Xem qua code thì mình thấy rằng ký tự ở vị trí thứ 2 đươc hoán đổi vị trí với 1 ký tự ở vị trí khác nhưng do mình không hiểu hết code nên không nó vị trí nó hoán đổi là vị trí nào nên mình đã thử hoán đổi với 4 ký tự còn lại.

![r2 1 1](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/2af649e7-7a5a-41a6-97bd-f91a72bcb7dc)

Sau vài lần thử thì mình thấy rằng vị tí thứ hai trong input được hoán đổi với vị trí cuối cùng của input.
Và thế là mình nhận được flag.

![r2 2 2](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/8632ba36-2528-4b5f-8fd5-52c07b742cc7)

> **Flag: pwn.college{cjylzG_XWMANJheFgkEZaxIYx6f.0FN1IDL3gDN3QzW}**

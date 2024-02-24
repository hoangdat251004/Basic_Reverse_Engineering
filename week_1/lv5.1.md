# **Babyrev_level5.1**

Với level này mình nghĩ rằng nó cũng gần giống level trước nhưng chắc sẽ không có gợi ý luôn nên mình mở chương trình bằng `IDA` để kiểm tra lấy thông tin trước.

Đúng như mình nghĩ chương trình cũng thực hiện việc `xor` input rồi sau đó mới đem đi so sánh với cái `'Expected result'` mà mình hay thấy( ở đây nó được đặt tên khác).

![r5 1 1](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/55db2125-02fc-46e6-9d33-dd399950b7d5)

![r5 1 2](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/95becea0-2407-4bf0-8be0-6e7699e1f41d)

Qua hai thông tin trên mình biết được từng ký tự trong chuỗi input sẽ được `xor` với key là `0xD0u`. Nhưng vẫn chưa rõ được rằng cái `'Expected result'` là gì nên mình lai tiếp tục tìm thêm.

Sau một hồi thì mình thấy có 1 biến `s2` lưu trữ 5 giá trị mà mình nghĩa đó chính là chuỗi `'Expected result'` dùng để so sánh với input của mình.

![r5 1 5](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/4771f066-b62f-409a-b929-312033b13916)

![r5 1 3](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/6430b95e-9da6-4d0e-b31b-63864bb1690b)

Thế là mình đã có đủ thông tin chuỗi `'Expected result'` và `key` mình đem đi `xor` và nhận được 1 chuỗi như dưới đây.

![r5 1 4](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/73450fa4-ff44-4cba-9784-c6255bb5cf21)

Nhập vào và thế là mình có được flag.

![r5 1 6](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/9fc1cab1-e887-44d9-9385-7d568164471f)

> **Flag: pwn.college{cYBgctdy23Gwkji6N6uY4VUdslB.0FM2IDL3gDN3QzW}**

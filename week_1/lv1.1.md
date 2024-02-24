**Babyrev_level1.1**

Level tiếp theo mình cũng nhận được 1 file như level trước và khi mình chạy file đó nó cũng yêu cầu mình nhập vào 1 chuỗi 5 ký tự vào để kiểm tra nhưng ta không rõ nó cụ kiểm tra ra sao.

![r1 1 1](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/83922a9c-4da1-4a3f-894e-f85b7f17bf18)

Do đó mình nghĩ tới việc mở file đó bằng IDA để xem cách chương trình hoạt động.

Sau khi xem qua thì mình thấy ở đây chương trình kiểm tra chuỗi nhập vào với 1 chuỗi `"evtvq"` ở trong biến `aEvtvq`, do đó khi nhập input `evtvq` thì mình nhận được flag của bài.

![r1 1 2](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/cf5efa24-e731-4dfd-855f-002c6dd2af17)

![r1 1 3](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/d92a497e-d13d-4e44-bcd8-ac616716f9fe)


> **Flag: pwn.college{sB9oiIU7lTpYSW-NwJJZMvOl0is.0lM1IDL3gDN3QzW}**

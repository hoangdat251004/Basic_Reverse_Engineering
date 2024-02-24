# **Babyrev_level5.0**

Ở level này khi mình chạy chương trình và nhập vào 1 chuỗi thì thấy rằng chuỗi mình vừa nhập được chuyển sang `hexa` và sau đó `xor` với key `0xb7` rồi so sánh với chuỗi `Expected result`.

![r5 0 1](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/b4eccac3-834e-471e-a37a-4c47307c7b17)

Thế nên mình đã mang chuỗi `Expected result` kia đi `xor` ngược lai với key `0xb7` để lấy chuỗi input đúng.

![r5 0 2](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/a084fbc6-d256-4d10-b46c-9c64763d02d8)

Sau đó mình có thể lấy được flag từ chương trình.

![r5 0 3](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/2081023a-f19c-419f-94a7-63704ca05b9c)


> **Flag: pwn.college{4lw7VAhWg6DPOo6yzxqZ3UBAjNf.0VO1IDL3gDN3QzW}**

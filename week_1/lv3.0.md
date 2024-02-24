# **Babyrev_level3.0**

Đến với level 3.0, mình quyết định kiểm tra chương trình bằng `IDA` trước xem nó có gì đặc biệt không thì mình thấy có 1 chuỗi khả nghi.

![r3 0 1](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/8d370b17-1134-4ef9-9a47-d9e576928254)


Khi mình dùng nó làm input thì nó chính là `Expectedd result` nhưng vị trí các ký tự đã bị thay đổi cụ thể là sắp xếp ngược lại trước khi so sánh với `Expected result`.

![r3 0 2](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/e8e400e2-afbc-464d-87ad-de4d7216a2ce)


Do đó chỉ việc đảo lại chuỗi là có thể nhận được flag.

![r3 0 3](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/2160a866-7565-40d0-bd94-c40a1af08570)


> **Flag: pwn.college{UaXURw7Uj4MBQXGPtJ2QXrD-dFN.0VN1IDL3gDN3QzW}**

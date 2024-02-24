# **Babyrev_level3.1**

Ở level này mình cũng mở chương trình bằng `IDA` trước để kiểm tra rồi mới chạy thử.

Sau khi xem qua code thì mình thấy chuỗi nhập vào được xử lý khá rối nhưng có thể hiểu được là chúng sẽ hoán đổi `vị trí ký tự thứ nhất` với `vị trí ký tự cuối cùng` với nhau và `vị trí ký tự thứ hai` với `vị trí ký tự thứ tư`, và rồi sau đó mới so sánh với chuỗi `cyeqg` như trong hình.

![r3 1 1](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/aa7acd6f-aed7-4b59-b80a-ceb2f76e7ad8)


Thế là chỉ việc đảo lại vị trí như level trước là có thể nhận được flag.

![r3 1 3](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/85c10859-e3ad-4073-b406-59e66db3624c)


> **Flag: pwn.college{M8zGmY9bs4_p7x9shhb_0EXU40y.0lN1IDL3gDN3QzW}**

# Babyrev_level6.0

Tại level này ta cũng được cho 1 file elf, chạy file đó thì ta thấy được cách hoạt động của file như hình dưới.

![r6 0 1](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/8f83dbe4-3839-40ce-8ebe-17f0fa779839)

Cơ bản thì ta nhập được 19 ký tự và chương trình sẽ thực hiện 1 số thao tác: `sort`,  `xor` với key, rồi sau đó so sánh với chuỗi của đề bài.

Để xử lý thì em mang chuỗi của đề bài đi `xor` ngược lại với `key` : `5ec1` và `181f` thì được 1 chuỗi input đúng.

Ở đây do chuỗi ta nhập vào sẽ được thự hiện sort ngay sau đó và chuỗi ta thu được cũng đang ở dạng tăng dần nên ta không cần thiết trong việc tìm lại vị trí ban đầu trước khi `sort`

![r6 0 2](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/afa741f1-c768-4504-ba4f-d3a83d0bf6c4)

![r6 0 3](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/697a8a43-e651-4a6b-aa49-84c09425fb25)

Nhập chuỗi emm tìm được vào thì em nhận được flag.

![r6 0 5](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/16ee4c84-b2c8-44c9-ac91-a2c12c5e38d9)


> **Flag: pwn.college{USSKOL2K6-hEqwR-Nc3auGMOFyJ.0VM2IDL3gDN3QzW}**

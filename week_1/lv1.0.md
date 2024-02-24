**Babyrev_level1.0**

Bắt đầu với level 1 ta nhận được 1 file elf như hình bên dưới.

![r1 0 0](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/8057ae1b-2a7a-41c3-86bd-c4ef03452d4a)

Khi ta thực thi file thì nó yêu cầu ta nhập vào 5 ký tự rồi chương trình sẽ chuyển đổi 5 ký tự đó sang dạng `base 16` hay `hexa` rồi so sánh với 1 chuỗi `Expected result`. Do chương trình chỉ nhận 5 ký tự đầu tiên ta nhập vào nên ta có thể thấy ký tự xuống dòng khi ta gõ `enter` bị chương trình loại bỏ.

![r1 0 1](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/7e2eb7d8-f99c-462c-bbeb-a766d4fa1b65)

Tìm cách để chuyển chuỗi `Expected result` sang dạng ký tự ta nhận được 1 input đúng của chương trình khi đó ta nhận được flag của bài.

![r1 0 3](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/dec196b5-5ae3-4662-99d3-1f03dfc28604)

Kết quả cuối cùng.

![r1 0 4](https://github.com/hoangdat251004/ehc_ctf_learn/assets/110254118/2ccb04dc-b8b0-4c26-9bda-7c43186909fd)


> **Flag: pwn.college{8dEa8g2rjUmKAUTIkyIczrx6hKF.0VM1IDL3gDN3QzW}** 

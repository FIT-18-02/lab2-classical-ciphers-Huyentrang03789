# Run Log – FIT4012 Lab 2

## Caesar Cipher
- [x] Đã chạy Caesar encrypt với `I LOVE YOU`, key `3`
   → Output: `L OVEH BRX`

- [x] Đã chạy Caesar encrypt với `hello world`, key `5`
   → Output: `mjqqt btwqi`

- [x] Đã chạy Caesar decrypt với `LORYH BRX`, key `3`
   → Output: `I LOVE YOU`

## Rail Fence Cipher
- [x] Đã chạy Rail Fence encrypt với `2` rails
   → Output: `IOEOLVYU`

- [x] Đã chạy Rail Fence encrypt với `4` rails
    → Output: `IYLOEUOV`

- [x] Đã chạy Rail Fence decrypt
    Input: `IOEOLVYU`, rails = 2  
  → Output: `ILOVEYOU`

## Validation / File input
- [x] Đã kiểm tra đầu vào không hợp lệ
  Input: `HELLO123`  
  → Output: `Invalid input. Only letters and spaces are allowed.`

- [x] Đã đọc dữ liệu từ `data/input.txt`
  Nội dung file: `HELLO WORLD`  
  → Output: `MJQQT BTWQI`

## Điều em học được từ bài lab
Viết 3-5 dòng ngắn gọn ở đây.
Qua bài lab, em hiểu được nguyên lý hoạt động của hai thuật toán mã hóa cổ điển là Caesar Cipher và Rail Fence Cipher. Em biết cách xử lý chuỗi trong C++, giữ nguyên dấu cách và phân biệt chữ hoa, chữ thường. Ngoài ra, em học được cách kiểm thử chương trình với nhiều test case và tổ chức mã nguồn trên GitHub một cách rõ ràng.

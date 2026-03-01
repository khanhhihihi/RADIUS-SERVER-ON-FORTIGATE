# RADIUS-SERVER-ON-FORTIGATE (PHÂN QUYỀN USER)
cách làm
Mình dùng 2 máy ảo là windows server 2022 và windows 11
windows server làm máy chủ, còn win 11 làm client để chạy fortigate
1, Build Radius server: https://cnttshop.vn/blogs/cong-cu-labs/huong-dan-build-radius-server-tren-windows-server-2016

2, Cấu hình fortigate:
trước khi có fortigate thì phải tải fortigate để cấu hình CLI
cách tải và cấu hình: https://www.youtube.com/watch?v=V2ScifxD-eU&t=695s
để mở được fortigate trên web thì phải để ip trong CLI giống bên win 
<img width="584" height="450" alt="image" src="https://github.com/user-attachments/assets/81c4dbc5-69fa-4d79-871e-fd7cce367a3f" />

3, Phân quyền USERs, ghi log, bảo mật
- user A: có thể vào được các trang web khác (dù không dùng mạng)
- user B: chặn truy cập 1 số trang web
Để hiện giao diện truy cập cho user: nên dùng neverssl.com

vid tham khảo của mình
!!! về vấn đề bảo mật thì hiện tại máy ảo của mình đang bị lỗi chứng chỉ gì gì đó k bic=))
[cauhinh1.zip](https://github.com/user-attachments/files/25663668/cauhinh1.zip)
[cauhinh2.zip](https://github.com/user-attachments/files/25663682/cauhinh2.zip)
[auhinh3.zip](https://github.com/user-attachments/files/25663685/auhinh3.zip)
CÒN LẠI HỎI CHAT NHÉ <3

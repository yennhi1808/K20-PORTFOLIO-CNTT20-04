không nhận ảnh
không đúng đường dẫn
hiện trang web

[2026-10-30 11:24] Báo lỗi hệ thống:
- Trang web không hiển thị hình ảnh và CSS do đường dẫn tài nguyên sai.
- File ket-qua.html đang dùng đường dẫn tuyệt đối Windows không hợp lệ trong trình duyệt: D:\CNTT20-04\portfolio\css\style.css
- Nên đổi sang đường dẫn tương đối hợp lệ như: css/style.css hoặc đúng thư mục chứa file CSS.
- File index.html cũng tham chiếu đến thư mục assets/ nhưng thư mục assets chưa tồn tại trong dự án.
- Kết quả: giao diện không load đúng, hình ảnh và phong cách trang bị mất, người dùng thấy "không nhận ảnh / không đúng đường dẫn / hiện trang web".
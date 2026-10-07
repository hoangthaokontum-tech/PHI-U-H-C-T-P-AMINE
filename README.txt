HƯỚNG DẪN SỬ DỤNG PHIẾU HỌC TẬP TƯƠNG TÁC
=========================================

1. Cách chạy:
- Giữ tất cả các file trong cùng 1 thư mục.
- Mở file index.html bằng bất kỳ trình duyệt web nào (Chrome, Edge, Safari...).

2. Cấu hình gửi điểm vào Google Sheets:
- Đã được tích hợp sẵn URL Web App của bạn vào app.js.
- Mỗi khi học sinh bấm "NỘP BÀI", dữ liệu sẽ tự động chuyển về Google Sheet (Sheet: TỔNG HỢP).

3. Cách tạo bài học mới / Thay đổi nội dung:
- TUYỆT ĐỐI KHÔNG sửa file index.html hay style.css.
- Chỉ mở file content.js bằng Notepad hoặc công cụ chỉnh sửa code (VS Code) và thay đổi dữ liệu trong biến LESSON_DATA.

4. Lưu ý về công thức hóa học:
Để hiển thị chỉ số dưới (ví dụ NH₃, CH₃), bạn dùng mã Unicode chỉ số chân trực tiếp trong content.js.
Hệ thống sẽ render và chấm điểm chính xác.

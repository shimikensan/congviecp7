# Pro Tasks Square Manager 📋

Ứng dụng quản lý nhiệm vụ chuyên nghiệp (To-do List) được thiết kế theo phong cách vuông vức (Square Style), tối ưu cho công việc và có khả năng cài đặt như một ứng dụng điện thoại (PWA).

## 🚀 Tính năng nổi bật

- **Giao diện Square Style**: Thiết kế góc cạnh, chuyên nghiệp, không bo tròn (Border-radius: 0).
- **Dashboard Thống kê**: Biểu đồ tròn trực quan giúp theo dõi tỷ lệ nhiệm vụ đúng hạn và quá hạn.
- **Tìm kiếm thông minh**: Lọc nhanh nhiệm vụ theo tên hoặc người thực hiện ngay tại giao diện chính.
- **Thùng rác (Trash)**: Bảo vệ dữ liệu, cho phép khôi phục các nhiệm vụ đã xóa nhầm.
- **Sao lưu & Khôi phục qua Zalo**: Xuất dữ liệu ra file `.json` để gửi qua Zalo hoặc lưu trữ dự phòng.
- **Thông báo quá hạn**: Hệ thống tự động kiểm tra và phát âm thanh cảnh báo khi nhiệm vụ đến hạn chót.
- **Chế độ tối (Dark Mode)**: Bảo vệ mắt khi làm việc ban đêm.
- **PWA Ready**: Có thể cài đặt trực tiếp lên màn hình chính điện thoại mà không cần thông qua App Store/Play Store.

## 🛠 Hướng dẫn cài đặt

1. Tải toàn bộ mã nguồn (`index.html`, `sw.js`, `manifest.json`).
2. Tải lên dịch vụ lưu trữ web (khuyên dùng **GitHub Pages** để sử dụng được tính năng PWA).
3. Truy cập vào đường dẫn URL của bạn trên trình duyệt điện thoại.
4. Chọn "Thêm vào màn hình chính" (Add to Home Screen) để sử dụng như một ứng dụng thực thụ.

## 📦 Cấu trúc dữ liệu

Ứng dụng sử dụng `localStorage` để lưu trữ dữ liệu trực tiếp trên trình duyệt của người dùng:
- `todo_pro_final`: Lưu danh sách nhiệm vụ hiện tại.
- `todo_trash`: Lưu danh sách các mục trong thùng rác.
- `dark_mode`: Lưu trạng thái giao diện.

## 🤝 Cách sao lưu và chuyển dữ liệu

1. Nhấn vào biểu tượng **Biểu đồ** trên thanh Header.
2. Nhấn nút **SAO LƯU** để tải file dữ liệu `.json` về máy.
3. Gửi file này qua Zalo cho thiết bị khác.
4. Trên thiết bị nhận, nhấn **KHÔI PHỤC** và chọn file vừa tải về để đồng bộ hóa dữ liệu.

---
*Phát triển để phục vụ công tác quản lý nhiệm vụ hiệu quả và an toàn.*
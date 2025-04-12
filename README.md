# 📚 iOS App Đọc Truyện / Đọc Sách
Ứng dụng iOS đọc sách &amp; truyện đơn giản, sử dụng SwiftUI và API để hiển thị nội dung truyện, không yêu cầu đăng nhập.

Dự án nhóm 4 người | Thời gian: 1.5 tháng  
Ứng dụng đọc sách/truyện sử dụng API (không có đăng nhập), giao diện đơn giản + một số chức năng phụ.

---

## ✅ Mục tiêu chính

- Hiển thị danh sách truyện/sách từ API
- Xem chi tiết truyện
- Đọc truyện theo chương
- Tích hợp một số chức năng nâng cao như:
  - 🔍 Tìm kiếm
  - 🌙 Giao diện Dark Mode
  - 🔖 Lưu truyện yêu thích (bookmark)
  - 🔔 Thông báo khi có truyện mới
  - 🔤 Điều chỉnh cỡ chữ khi đọc

---

## 🗂️ Chức năng chính

| Màn hình             | Mô tả                                           | Bắt buộc |
|----------------------|--------------------------------------------------|----------|
| Trang chủ (Home)     | Hiển thị danh sách truyện                       | ✅        |
| Chi tiết truyện      | Xem mô tả, ảnh bìa, tác giả,...                 | ✅        |
| Màn đọc truyện       | Hiển thị nội dung chương                       | ✅        |
| Tìm kiếm             | Lọc truyện theo tên                             | ✅        |
| Bookmark             | Lưu truyện yêu thích                            | ❌ Tuỳ chọn |
| Thông báo mới        | Hiển thị thông báo khi có truyện mới cập nhật   | ❌ Tuỳ chọn |
| Tăng giảm cỡ chữ     | Tùy chỉnh kích cỡ chữ khi đọc                   | ❌ Tuỳ chọn |
| Giao diện dark mode  | Tự động theo hệ thống                           | ✅        |

---

## 👨‍💻 Phân công nhóm

| Thành viên | Vai trò | Công việc cụ thể |
|------------|--------|------------------|
| **Bạn A**  | UI Design | Home, Detail, Reader View |
| **Bạn B**  | API + Model | Tạo model `Book`, `Chapter`, `APIService` |
| **Bạn C**  | Tính năng phụ | Search, Dark Mode, Bookmark, Font Size |
| **Bạn D**  | Notification + Test + Report | Thông báo truyện mới, test, viết báo cáo |

---

## 🧭 Timeline đề xuất

| Tuần | Công việc chính |
|------|-----------------|
| Tuần 1 | Tạo project, chia task, thiết kế giao diện cơ bản |
| Tuần 2 | Tạo Model dữ liệu, gọi API mẫu |
| Tuần 3 | Hiển thị danh sách truyện + Chi tiết + Màn đọc |
| Tuần 4 | Làm các tính năng phụ: search, bookmark, dark mode |
| Tuần 5 | Thêm thông báo mới, xử lý lỗi |
| Tuần 6 | Tổng hợp, test, viết báo cáo, chuẩn bị demo |

---

## 🚀 Công nghệ sử dụng

- Swift + SwiftUI
- URLSession để gọi API
- `@State`, `@ObservableObject` để quản lý trạng thái
- `UserDefaults` hoặc `@AppStorage` để lưu dữ liệu local
- `UNUserNotificationCenter` cho Local Notifications

---

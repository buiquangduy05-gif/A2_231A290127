# BÁO CÁO LAB A2 - VÒNG ĐỜI ACTIVITY & LƯU TRẠNG THÁI

- **Sinh viên thực hiện**: Bùi Quang Duy
- **MSSV**: 231A290127
- **Tên Repository**: A2_231A290127

---

## CÁC BÀI NÂNG CAO ĐÃ THỰC HIỆN:

### 1. Nâng cao NC2: Tùy chọn tạm dừng khi ứng dụng ra nền
- **Mô tả**: Bổ sung một `CheckBox` ("Dừng khi ra nền") trên giao diện.
- **Logic thực hiện**: Trong phương thức `onStop()`, kiểm tra nếu CheckBox được tích chọn và đồng hồ đang chạy thì gọi hàm tạm dừng đếm giờ (`pauseTimer()`).

### 2. Nâng cao NC3: Đổi màu hiển thị thời gian & Hiệu ứng rung
- **Mô tả 1**: Khi thời gian đếm vượt quá 60 giây (1 phút), chữ số hiển thị đồng hồ tự động chuyển từ màu đen sang màu đỏ (`Color.RED`).
- **Mô tả 2**: Cấp quyền `VIBRATE` trong `AndroidManifest.xml` và kích hoạt rung phản hồi xúc giác nhẹ (100ms) khi người dùng bấm nút **Đặt lại**.

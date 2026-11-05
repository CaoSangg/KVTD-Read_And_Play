# PROJECT WEB ĐỌC TRUYỆN VÀ GAME KHÁM PHÁ THẾ GIỚI KHẤU VẤN TIÊN ĐẠO GAME 2.5D

Dự án kết hợp giữa **Nền tảng đọc truyện tương tác** và **Game nhập vai thế giới mở 2.5D**, triển khai với quy trình **CI/CD tự động bằng GitHub Actions lên Vercel**.

---

## 1. Cấu Trúc Dự Án Hiện Tại

```text
d:/MyProject/
├── preview_landing_chamber.html      # Bản xem trước giao diện Thư Phòng tương tác (mở xem ngay)
├── .github/
│   └── workflows/
│       └── deploy.yml                # File CI/CD GitHub Actions hoàn chỉnh
└── README.md
```

---

## 2. Hướng Dẫn Xem Thử Giao Diện Ngay Lập Tức

Bạn có thể mở trực tiếp file `preview_landing_chamber.html` bằng trình duyệt Chrome, Edge hoặc Cốc Cốc trên máy tính:
1. Mở thư mục `D:\MyProject`.
2. Click đúp chuột vào file **`preview_landing_chamber.html`**.
3. **Trải nghiệm**:
   * Các hạt bụi linh khí lơ lửng và màn sương mù chuyển động trong không gian.
   * Rê chuột qua **Cổ Thư Tàng Kinh**, **Ngọc Phật Bổn Mệnh** hoặc **Cửu Châu Cổ Đồ** để thấy hiệu ứng hào quang tỏa sáng, bảo vật bay bổng lên nhẹ.
   * Click chuột vào từng bảo vật để mở màn hình chuyển hướng tương ứng (Vào đọc truyện hoặc Xuyên không vào game).

---

## 3. Cấu Hình CI/CD Pipeline với GitHub Actions

Khi đẩy code lên GitHub sẽ tự động kích hoạt:
1. **Kiểm tra code**: Máy ảo Ubuntu tự động cài đặt thư viện và build và test thử nghiệm để bắt lỗi.
2. **Deploy lên Vercel**: Sau khi build thành công, tự động deploy website live ra Internet.

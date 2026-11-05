# PROJECT WEB ĐỌC TRUYỆN VÀ GAME KHÁM PHÁ THẾ GIỚI KHẤU VẤN TIÊN ĐẠO GAME 2.5D

Dự án kết hợp giữa **Nền tảng đọc truyện tương tác** và **Game nhập vai thế giới mở 2.5D**, triển khai với quy trình **CI/CD tự động bằng GitHub Actions lên Vercel**.

---

## 1. Cấu Trúc Dự Án Hiện Tại

```text
d:/MyProject/
├── index.html                        # Home page hiện tại
|-- reader.html                       # Page đọc truyện 
├── .github/ 
│   └── workflows/
│       └── deploy.yml                # File CI/CD pipeline tạm
|-- images/                           # Các ảnh liên quan đến project 
└── README.md
```

---

## 2. Trải Nghiệm:
   * Các hạt bụi linh khí lơ lửng và màn sương mù chuyển động trong không gian.
   * Rê chuột qua Cổ Thư, Sơn Hà Đồ và Ngọc Phật để trải nghiệm các tính năng. 

---

## 3. Cấu Hình tạm CI/CD Pipeline

Khi đẩy code lên GitHub sẽ tự động kích hoạt:
1. Kiểm tra code: Máy ảo Ubuntu tự động cài đặt thư viện và build và test thử nghiệm để bắt lỗi.
2. Deploy lên Vercel: Sau khi build thành công, tự động deploy website live ra Internet.

# Ứng Dụng Máy Tính Cầm Tay Flutter

## Mô Tả Dự Án

Đây là một ứng dụng **máy tính cầm tay** hoàn chỉnh được xây dựng bằng **Flutter**. Ứng dụng thực hiện tất cả các phép tính cơ bản và có thêm nhiều tính năng nâng cao nhằm cải thiện trải nghiệm người dùng.

### Các Tính Năng Chính
- **Phép tính cơ bản:** Cộng (+), Trừ (-), Nhân (×), Chia (÷)
- **Hỗ trợ số thập phân:** Ví dụ `3.5 × 2 = 7`
- **Hỗ trợ số âm:** Ví dụ `-5 + 3`
- **Clear (C) và Clear End (CE):** Xóa toàn bộ hoặc xóa ký tự cuối
- **Phần trăm (%):** Chuyển đổi số sang phần trăm
- **Dấu ±:** Đổi dấu số vừa nhập
- **Dấu ngoặc ( ) :** Nhóm biểu thức
- **Lịch sử tính toán:** Hiển thị các biểu thức và kết quả trước đó
- **UI responsive:** Nút và bố cục tương ứng với thiết kế Figma
- **Xử lý lỗi:** Ngăn chia cho 0, nhiều dấu chấm, nhấn liên tiếp phép tính
- **Giao diện tối:** Thiết kế tối mượt mà, dễ nhìn

Ứng dụng mang đến trải nghiệm **máy tính trực quan**, cập nhật kết quả ngay khi nhập mà không bị reset cho tới khi tính toán xong.

---

## Ảnh Minh Họa

| ![Screen1](https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005346896_283a0e41301812e20238f0614cc031e7_tquwhh.jpg) | ![Screen2](https://res.cloudinary.com/dq64aidpx/image/upload/v1763216590/z7228005345564_28fa0828436553ae6814f91206be9bb4_fcpiuy.jpg) | ![Screen3](https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005351744_45a9360c9ff71958a8f9416e9cb7bd47_lgc2iw.jpg) |
|---|---|---|
| ![Screen4](https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005372358_8a4fca763c21df78d16335244e9d4e74_j7l6h4.jpg) | ![Screen5](https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005377623_d80a286ef732a8869391c85658bee45a_ixwtol.jpg) | ![Screen6](https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005386492_4cd6d37ea490379b2748c91456dc2324_icys0l.jpg) |

---

## Hướng Dẫn Chạy Ứng Dụng

1. **Clone repository:**  
   Vào GitHub và sao chép repository:  
   `https://github.com/Truongson-erorr/flutter_calculator_CaoNienTruongSon.git`

2. **Đi vào thư mục dự án:**  
   Mở terminal và vào thư mục dự án:  
   `cd flutter_calculator_CaoNienTruongSon`

3. **Cài đặt dependencies:**  
   Chạy lệnh sau để cài các thư viện cần thiết:  
   `flutter pub get`

4. **Chạy ứng dụng:**  
   Chạy ứng dụng trên emulator hoặc thiết bị thật:  
   `flutter run`

---

## Các Tính Năng Bổ Sung

- **Bảng lịch sử tính toán:** Hiển thị tất cả các biểu thức và kết quả trước đó để dễ tham khảo.
- **Kích thước chữ nút responsive:** Điều chỉnh kích thước chữ cho các nút đặc biệt như CE (20) và ( ) (22).
- **Xử lý lỗi:** Ngăn chia cho 0, nhiều dấu thập phân, và nhấn liên tiếp các phép tính.
- **Phản hồi tức thì:** Màn hình hiển thị cập nhật ngay khi nhập, không reset cho tới khi tính toán hoàn tất.
- **Giao diện tối:** Thiết kế tối mượt mà, dễ nhìn và dễ sử dụng.
- **Sẵn sàng mở rộng:** Có thể thêm chức năng chuyển đổi giữa giao diện sáng/tối trong tương lai.

---

## Cấu Trúc Lưu Trữ Dự Án

```text
lib/
├── main.dart                 # Entry point của ứng dụng
├── screen/                   # Chứa các màn hình và UI
│   ├── calculatorUI.dart     # Giao diện chính của máy tính
│   └── logic.dart            # Xử lý logic tính toán
└── screenshot/               # Thư mục chứa ảnh minh họa từ điện thoại thật
    ├── screen1.jpg
    ├── screen2.jpg
    ├── screen3.jpg
    ├── screen4.jpg
    ├── screen5.jpg
    └── screen6.jpg
pubspec.yaml                  # File cấu hình Flutter & dependencies
README.md                     # Mô tả dự án
.gitignore                    # File ignore các thư mục sinh tự động (build/, .dart_tool/, v.v.)

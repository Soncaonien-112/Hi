# Ứng Dụng Máy Tính Cầm Tay Flutter

## Mô Tả Dự Án

- Đây là một ứng dụng máy tính cầm tay hoàn chỉnh được xây dựng bằng Flutter. Ứng dụng mang đến trải nghiệm tính toán trực quan, nhanh chóng và hiện đại trên điện thoại di động.

- Ứng dụng thực hiện tất cả các phép tính cơ bản như cộng, trừ, nhân, chia. Ngoài ra, nó còn hỗ trợ số thập phân, số âm, và phần trăm, giúp người dùng dễ dàng thực hiện các phép tính phức tạp.

- Giao diện được thiết kế theo phong cách dark theme, giúp giảm mỏi mắt khi sử dụng lâu. Các nút bấm được bố trí responsive theo thiết kế Figma, đảm bảo trải nghiệm mượt mà và trực quan.

- Ứng dụng tích hợp bảng lịch sử tính toán, cho phép người dùng xem lại tất cả các phép tính trước đó cùng kết quả. Điều này hỗ trợ việc kiểm tra và đối chiếu nhanh chóng.

- Các tình huống lỗi như chia cho 0, nhập nhiều dấu thập phân, hoặc nhấn liên tiếp các phép tính được xử lý thông minh, giúp trải nghiệm luôn ổn định.

- Ứng dụng kết hợp UI/UX hiện đại, quản lý trạng thái linh hoạt, và logic toán học chính xác, phù hợp với học sinh, sinh viên, và những ai cần công cụ tính toán nhanh trên thiết bị di động.

- Trong tương lai, ứng dụng có thể mở rộng thêm các tính năng như chuyển đổi giao diện sáng/tối, thêm biểu đồ, hoặc các chức năng nâng cao khác, tạo nên một máy tính di động toàn diện.

### Các Tính Năng Chính
- ✅ **Phép tính cơ bản:** Cộng (+), Trừ (-), Nhân (×), Chia (÷)
- ✅ **Hỗ trợ số thập phân:** Ví dụ `3.5 × 2 = 7`
- ✅ **Hỗ trợ số âm:** Ví dụ `-5 + 3`
- ✅ **Clear (C) và Clear End (CE):** Xóa toàn bộ hoặc xóa ký tự cuối
- ✅ **Phần trăm (%):** Chuyển đổi số sang phần trăm
- ✅ **Dấu ±:** Đổi dấu số vừa nhập
- ✅ **Dấu ngoặc:** Nhóm biểu thức
- ✅ **Lịch sử tính toán:** Hiển thị các biểu thức và kết quả trước đó
- ✅ **UI responsive:** Nút và bố cục tương ứng với thiết kế Figma
- ✅ **Xử lý lỗi:** Ngăn chia cho 0, nhiều dấu chấm, nhấn liên tiếp phép tính
- ✅ **Giao diện tối:** Thiết kế tối mượt mà, dễ nhìn

Ứng dụng mang đến trải nghiệm **máy tính trực quan**, cập nhật kết quả ngay khi nhập mà không bị reset cho tới khi tính toán xong.

---

## 📸 Ảnh Minh Họa
4KG2VgKFDJWqdtg4UMRqk5CnkJVoCpe5QMd20Pf7.jpg
| <4KG2VgKFDJWqdtg4UMRqk5CnkJVoCpe5QMd20Pf7.jpg width="200"> | <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216590/z7228005345564_28fa0828436553ae6814f91206be9bb4_fcpiuy.jpg" width="200"> | <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005351744_45a9360c9ff71958a8f9416e9cb7bd47_lgc2iw.jpg" width="200"> |
|---|---|---|
| <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005372358_8a4fca763c21df78d16335244e9d4e74_j7l6h4.jpg" width="200"> | <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005377623_d80a286ef732a8869391c85658bee45a_ixwtol.jpg" width="200"> | <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005386492_4cd6d37ea490379b2748c91456dc2324_icys0l.jpg" width="200"> |

---

## 🛠 Hướng Dẫn Chạy Ứng Dụng

1. **Clone repository:**  
   `https://github.com/Truongson-erorr/flutter_calculator_CaoNienTruongSon.git`

2. **Đi vào thư mục dự án:**  
   `cd flutter_calculator_CaoNienTruongSon`

3. **Cài đặt dependencies:**  
   `flutter pub get`

4. **Chạy ứng dụng:**  
   `flutter run` trên emulator hoặc thiết bị thật
   
5. **Chạy trên thiết bị cụ thể (tùy chọn):**  
   `flutter run -d <device_id>`
   
7. **Xây dựng bản release (tùy chọn):**  
   Tạo APK cho Android:  `flutter build apk --releas`  
   Tạo IPA cho iOS:  `flutter build ios --release`  
   
8. **Lưu ý quan trọng:**  
   Đảm bảo thiết bị hoặc emulator đang bật chế độ debug.  
   Nếu gặp lỗi dependencies, thử:  
   `flutter clean`  
   `flutter pub get`  
   Phiên bản Flutter nên là stable.  

Lịch sử tính toán sẽ tự cập nhật sau mỗi phép tính, không cần thao tác thêm.

---

## ✨ Các Tính Năng Bổ Sung

- 📝 **Bảng lịch sử tính toán:** Hiển thị tất cả các biểu thức và kết quả trước đó để dễ tham khảo
- 🔠 **Kích thước chữ nút responsive:** Điều chỉnh chữ cho CE (20) và ( ) (22)
- ⚠️ **Xử lý lỗi:** Ngăn chia cho 0, nhiều dấu thập phân, nhấn liên tiếp phép tính
- ⚡ **Phản hồi tức thì:** Màn hình cập nhật ngay khi nhập
- 🌙 **Giao diện tối:** Thiết kế mượt mà, dễ nhìn
- 🚀 **Sẵn sàng mở rộng:** Có thể thêm chuyển đổi sáng/tối trong tương lai

---

## 🗂 Cấu Trúc Lưu Trữ Dự Án

```text
lib/
├── main.dart                 # Entry point của ứng dụng
├── screen/                   # Chứa các màn hình và UI
│   ├── calculator_screens.dart     # Giao diện chính của máy tính
│   └── calculator_logic.dart        # Xử lý logic tính toán
└── screenshot/               # Thư mục chứa ảnh minh họa từ điện thoại thật
    ├── screen1.jpg
    ├── screen2.jpg
    ├── screen3.jpg
    ├── screen4.jpg
    ├── screen5.jpg
    └── screen6.jpg
pubspec.yaml                  # File cấu hình Flutter & dependencies
README.md                     # Mô tả dự án
.gitignore                    # Ignore các thư mục sinh tự động

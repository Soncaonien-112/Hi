# Ứng Dụng Máy Tính Flutter

## Mô Tả Dự Án

Đây là một ứng dụng **máy tính cầm tay đầy đủ chức năng** được xây dựng bằng **Flutter**. Ứng dụng thực hiện tất cả các phép tính cơ bản và bao gồm các tính năng bổ sung nhằm nâng cao trải nghiệm người dùng.  

### Các Tính Năng Chính:
- **Phép tính cơ bản:** Cộng (+), Trừ (-), Nhân (×), Chia (÷)
- **Hỗ trợ số thập phân:** Thực hiện các phép tính với số thập phân như `3.5 × 2 = 7`
- **Số âm:** Hỗ trợ nhập số âm (ví dụ: `-5 + 3`)
- **Chức năng Xóa (C) và Xóa ký tự cuối (CE):** Reset toàn bộ hoặc xóa ký tự cuối
- **Phần trăm (%):** Chuyển số thành phần trăm
- **Đổi dấu (±):** Đổi dấu số cuối
- **Dấu ngoặc ( )**: Cho phép nhóm biểu thức
- **Lịch sử tính toán:** Hiển thị các biểu thức và kết quả trước đó
- **Giao diện responsive:** Nút và bố cục phù hợp với thiết kế Figma
- **Xử lý lỗi:** Ngăn chia cho 0 và nhiều dấu chấm thập phân
- **Giao diện tối:** Thiết kế tối mượt mà, dễ nhìn

Ứng dụng cung cấp trải nghiệm **máy tính trực quan** với phản hồi tức thì khi người dùng nhập dữ liệu.

---

## Ảnh Chụp Màn Hình

### Ảnh Màn Hình Ứng Dụng

| <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005346896_283a0e41301812e20238f0614cc031e7_tquwhh.jpg" width="200"> | <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216590/z7228005345564_28fa0828436553ae6814f91206be9bb4_fcpiuy.jpg" width="200"> | <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005351744_45a9360c9ff71958a8f9416e9cb7bd47_lgc2iw.jpg" width="200"> |
|---|---|---|
| <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005372358_8a4fca763c21df78d16335244e9d4e74_j7l6h4.jpg" width="200"> | <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005377623_d80a286ef732a8869391c85658bee45a_ixwtol.jpg" width="200"> | <img src="https://res.cloudinary.com/dq64aidpx/image/upload/v1763216591/z7228005386492_4cd6d37ea490379b2748c91456dc2324_icys0l.jpg" width="200"> |

---

## Hướng Dẫn Chạy Ứng Dụng

Làm theo các bước sau để chạy ứng dụng máy tính:

1. **Clone repository**  
   Truy cập GitHub và clone repository:  
   `https://github.com/Truongson-erorr/flutter_calculator_CaoNienTruongSon.git`

2. **Đi vào thư mục dự án**  
   Mở terminal và đi vào thư mục dự án:  
   `cd flutter_calculator_CaoNienTruongSon`

3. **Cài đặt các dependencies**  
   Đảm bảo bạn đã cài Flutter. Sau đó chạy:  
   `flutter pub get`  

4. **Chạy ứng dụng**  
   Chạy app trên emulator hoặc thiết bị thực tế:  
   `flutter run`  

---

## Các Tính Năng Bổ Sung

- **Bảng lịch sử tính toán:** Hiển thị tất cả các biểu thức và kết quả trước đó để dễ tham khảo.
- **Kích thước chữ nút responsive:** Điều chỉnh kích thước chữ cho các nút đặc biệt như CE (20) và ( ) (22).
- **Xử lý lỗi:** Ngăn chia cho 0, nhiều dấu thập phân, và nhấn liên tiếp các phép tính.
- **Phản hồi tức thì:** Màn hình hiển thị cập nhật ngay khi nhập, không reset cho tới khi tính toán hoàn tất.
- **Giao diện tối:** Thiết kế tối mượt mà, dễ nhìn và dễ sử dụng.
- **Sẵn sàng mở rộng:** Có thể thêm chức năng chuyển đổi giữa giao diện sáng/tối trong tương lai.

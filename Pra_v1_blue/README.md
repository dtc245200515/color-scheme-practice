# Phiên Bản 1: Phối Màu Xanh (Blue Theme)

## Thông Tin Bài Thực Hành
- **Tiêu đề**: Luyện tập phối màu đơn tông trên trang web
- **Màu chính**: #00ADEE (Xanh dương)
- **Phương pháp**: Sử dụng bảng màu đơn tông với 9 bậc

## Bảng Màu Được Sử Dụng

| Bậc | Mã Hex | Mô Tả |
|-----|--------|-------|
| 1 | #00ADEE | Màu chính (xanh đậm) |
| 2 | #00B2EF | Xanh bậc 2 |
| 3 | #00B8F2 | Xanh bậc 3 |
| 4 | #00BFF2 | Xanh bậc 4 (banner background) |
| 5 | #00C5F5 | Xanh bậc 5 |
| 6 | #00CCF7 | Xanh bậc 6 |
| 7 | #8DD7F7 | Xanh bậc 7 (preview background) |
| 8 | #A6DFFB | Xanh bậc 8 |
| 9 | #C6E9FA | Xanh bậc 9 (info section) |

## Các Thay Đổi Được Thực Hiện

### 1. Banner (Phần tiêu đề chính)
- **Màu nền**: Thay từ #c33 (đỏ) sang #00BFF2 (xanh bậc 4)
- **Màu chữ**: Thay từ #eee (trắng) sang #000 (đen)
- **Hiệu ứng bóng chữ**: Loại bỏ (text-shadow: none)

### 2. Nút "Add to Cart" (trong banner)
- **Màu nền**: Thay từ #b23434 (đỏ đậm) sang #00ADEE (xanh bậc 1)
- **Màu chữ**: Giữ #fff (trắng)
- **Hover state**: Thay background sang rgba(0, 173, 238, 0.8)
- **Active state**: Thay sang #0088BB (xanh đậm hơn)

### 3. Phần "PREVIEW" (Product preview)
- **Màu nền liên kết**: Thay từ #fac7d2 (hồng) sang #8DD7F7 (xanh bậc 7)
- **Màu chữ**: Giữ #000 (đen)
- **Nhãn "PREVIEW" (banner chéo)**: Thay từ #fe0000 (đỏ) sang #00ADEE (xanh)
- **Vòng tròn play button**: Thay từ #fe0000 (đỏ) sang #00ADEE (xanh)

### 4. Phần nội dung bên phải (Aside content)
- **Nút "Go to Album"**: Thay từ #c33 (đỏ) sang #00ADEE (xanh)
- **Hover button**: rgba(0, 173, 238, 0.8)

### 5. Phần "ON SALE" (Badge)
- **Màu nền**: Thay từ rgba(255, 0, 0, 0.7) sang rgba(0, 173, 238, 0.7)
- **Màu chữ**: Giữ #fff (trắng)

### 6. Phần thông tin (Info section)
- **Màu nền**: Thay từ #ccc (xám) sang #C6E9FA (xanh bậc 9)
- **Các thành phần trong phần**: Giữ nguyên

## Nguyên Tắc Phối Màu

1. **Màu chính**: #00ADEE được sử dụng cho các nút action và điểm nhấn
2. **Màu nền chính**: #00BFF2 cho header banner
3. **Màu nhạt dần**: Từ bậc 4 đến bậc 9 tạo cảm giác hòa hợp và dễ đọc
4. **Độ tương phản**: Sử dụng màu đen (#000) cho chữ trên nền nhạt để đảm bảo dễ đọc
5. **Điểm nhấn**: Các nút chính sử dụng màu đậm nhất (#00ADEE) để thu hút sự chú ý

## Tệp Được Sửa Đổi
- `style.css` - Chứa tất cả các thay đổi CSS

## Cách Chạy
1. Mở file `index.html` trong trình duyệt web
2. Hoặc chạy server HTTP: `python -m http.server 8000` (trong Windows PowerShell)
3. Truy cập: http://localhost:8000

## Kết Quả
Trang web hiện có giao diện phối màu xanh dương đơn tông, tạo cảm giác chuyên nghiệp, sạch sẽ và hiện đại.

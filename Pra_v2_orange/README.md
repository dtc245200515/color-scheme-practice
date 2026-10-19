# Phiên Bản 2: Phối Màu Cam (Orange Theme)

## Thông Tin Bài Thực Hành
- **Tiêu đề**: Luyện tập phối màu đơn tông trên trang web
- **Màu chính**: #FF8C00 (Cam đậm)
- **Phương pháp**: Sử dụng bảng màu đơn tông với 9 bậc

## Bảng Màu Được Sử Dụng

| Bậc | Mã Hex | Mô Tả |
|-----|--------|-------|
| 1 | #FF8C00 | Màu chính (cam đậm) |
| 2 | #FFA500 | Cam bậc 2 |
| 3 | #FFAA11 | Cam bậc 3 |
| 4 | #FFB84D | Cam bậc 4 (banner background) |
| 5 | #FFC266 | Cam bậc 5 |
| 6 | #FFCC80 | Cam bậc 6 |
| 7 | #FFD699 | Cam bậc 7 |
| 8 | #FFE0B2 | Cam bậc 8 (preview background) |
| 9 | #FFECB3 | Cam bậc 9 (info section) |

## Các Thay Đổi Được Thực Hiện

### 1. Banner (Phần tiêu đề chính)
- **Màu nền**: Thay từ #c33 (đỏ) sang #FFB84D (cam bậc 4)
- **Màu chữ**: Thay từ #eee (trắng) sang #000 (đen)
- **Hiệu ứng bóng chữ**: Loại bỏ (text-shadow: none)

### 2. Nút "Add to Cart" (trong banner)
- **Màu nền**: Thay từ #b23434 (đỏ đậm) sang #FF8C00 (cam bậc 1)
- **Màu chữ**: Giữ #fff (trắng)
- **Hover state**: Thay background sang rgba(255, 140, 0, 0.8)
- **Active state**: Thay sang #E67E00 (cam đậm hơn)

### 3. Phần "PREVIEW" (Product preview)
- **Màu nền liên kết**: Thay từ #fac7d2 (hồng) sang #FFE0B2 (cam bậc 8)
- **Màu chữ**: Giữ #000 (đen)
- **Nhãn "PREVIEW" (banner chéo)**: Thay từ #fe0000 (đỏ) sang #FF8C00 (cam)
- **Vòng tròn play button**: Thay từ #fe0000 (đỏ) sang #FF8C00 (cam)

### 4. Phần nội dung bên phải (Aside content)
- **Nút "Go to Album"**: Thay từ #c33 (đỏ) sang #FF8C00 (cam)
- **Hover button**: rgba(255, 140, 0, 0.8)

### 5. Phần "ON SALE" (Badge)
- **Màu nền**: Thay từ rgba(255, 0, 0, 0.7) sang rgba(255, 140, 0, 0.7)
- **Màu chữ**: Giữ #fff (trắng)

### 6. Phần thông tin (Info section)
- **Màu nền**: Thay từ #ccc (xám) sang #FFECB3 (cam bậc 9)
- **Các thành phần trong phần**: Giữ nguyên

## Nguyên Tắc Phối Màu

1. **Màu chính**: #FF8C00 được sử dụng cho các nút action và điểm nhấn
2. **Màu nền chính**: #FFB84D cho header banner
3. **Màu nhạt dần**: Từ bậc 4 đến bậc 9 tạo gradient nhẹ nhàng và ấm áp
4. **Độ tương phản**: Sử dụng màu đen (#000) cho chữ trên nền để đảm bảo dễ đọc
5. **Điểm nhấn**: Các nút chính sử dụng màu cam đậm nhất (#FF8C00) tạo sự năng động
6. **Cảm giác**: Màu cam tạo cảm giác ấm áp, thân thiện, năng lượng cao

## Tệp Được Sửa Đổi
- `style.css` - Chứa tất cả các thay đổi CSS

## Cách Chạy
1. Mở file `index.html` trong trình duyệt web
2. Hoặc chạy server HTTP: `python -m http.server 8001` (trong Windows PowerShell)
3. Truy cập: http://localhost:8001

## So Sánh Với Phiên Bản 1 (Xanh)
- **Phiên bản 1**: Tạo cảm giác chuyên nghiệp, mát mẻ, tin cậy
- **Phiên bản 2**: Tạo cảm giác ấm áp, năng động, vui tươi

## Kết Quả
Trang web hiện có giao diện phối màu cam đơn tông, tạo cảm giác tươi sáng, năng lượng và thân thiện với người dùng.

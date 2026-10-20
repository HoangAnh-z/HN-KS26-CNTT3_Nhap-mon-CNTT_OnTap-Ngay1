# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Bùi Hoàng Anh
- **Lớp:** HN-K26 CNTT3
- **Link repository:** https://github.com/HoangAnh-z/HN-KS26-CNTT3_Nhap-mon-CNTT_OnTap-Ngay1.git
- **Hệ điều hành (Windows/macOS):** MacOS

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)
```bash
cd Documents/trung-tam-tieng-anh
# B1
pwd
# B2
ls -a
# B3
mv lich_hoc.txt docs ; mv logo_trung_tam.png anh_lop_hoc.jpg media
# B4
cp media/logo_trung_tam.png archive
# B5
rm temp_201.tmp ; rm temp_202.tmp
# B6
cd ./logs ; ls -la ; cd ..
# B7
cd docs ; cp ../media/anh_lop_hoc.jpg ../archive/ ; cd. ..

```

### Kết quả B1 (pwd)

```text

/Users/julia/Documents/trung-tam-tieng-anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text

.			.env			data			media
..			archive			docs
.DS_Store		bai_lam_ngay1.md	logs

./archive:
.			..			anh_lop_hoc.jpg		logo_trung_tam.png

./data:
.			..			hoc_vien_khoa_3.xlsx

./docs:
.		..		.DS_Store	lich_hoc.txt

./logs:
.		..		.DS_Store	access.log

./media:
.			.DS_Store		logo_trung_tam.png
..			anh_lop_hoc.jpg


```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
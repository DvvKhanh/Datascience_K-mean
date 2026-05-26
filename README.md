# KHOA HỌC DỮ LIỆU
# Họ tên: Đậu Văn Khánh
# MSSV: K225480106099
# Lớp: K58KTP
# Link video: https://www.youtube.com/watch?v=GTHHN_3tJ0o

## Cấu trúc thư mục
```
BT_K-mean/
│
├── BangDiemK58KTP.xlsx
│   → File dữ liệu điểm sinh viên
│
├── K-mean.ipynb
│   → File code Python/Jupyter Notebook
│
├── KetQua_XepLoai_GPA.xlsx
│   → File kết quả sau khi xử lý GPA
│
├── bieu_do_cot.png
│   → Biểu đồ cột thống kê xếp loại sinh viên
│
├── bieu_do_kmeans.png
│   → Biểu đồ phân cụm K-Means theo GPA
│
└── bieu_do_tron.png
    → Biểu đồ tròn tỷ lệ xếp loại sinh viên
```

## Cách chạy chương trình
### Bước 1: Tải folder BT_K-mean
- Đầu tiên:
  + Tải project BT_K-mean từ GitHub về máy.
  + Sau đó giải nén file .zip.
- Trong folder đã có sẵn:
  + File code Python và file dữ liệu Excel BangDiemK58KTP.xlsx.
  
### Bước 2: Mở project bằng môi trường lập trình Python
- Mở một môi trường lập trình Python bất kỳ, ví dụ:
  + Visual Studio Code (VS Code)
  + PyCharm
  + Jupyter Notebook
  + Google Colab
- Sau đó mở folder: BT_K-mean
- Tiếp theo mở file: K-mean.ipynb để chạy chương trình.

### Bước 3: Cài các thư viện cần thiết
- Mở Terminal hoặc Command Prompt trong môi trường lập trình và nhập lệnh:
```pip install pandas numpy matplotlib openpyxl scikit-learn```
- Sau đó nhấn biểu tượng ▶ (Run) ở bên trái ô code để thực thi chương trình.

### Bước 4: Mở file code
- Trong folder project mở file: K-mean.ipynb
- Đây là file chứa toàn bộ code chương trình:
  + Đọc dữ liệu Excel.
  + Tính GPA.
  + Phân loại học lực.
  + Phân cụm K-Means.
  + Vẽ biểu đồ.
  + Xuất file Excel kết quả.
 
### Bước 5: Chọn môi trường Python
- Nếu phần mềm yêu cầu chọn Python Interpreter hoặc Kernel thì chọn: Python 3.x

### Bước 6: Chạy chương trình
- Có thể chạy bằng:
  + Nút Run All
  + Hoặc chạy từng cell bằng: Shift + Enter hoặc nhấn biểu tượng ▶ (Run) ở bên trái ô code để thực thi chương trình.

## Kết quả sau khi chạy
Chương trình sẽ tự động:
- Hiển thị:
  + Danh sách sinh viên Giỏi
  + Danh sách sinh viên Khá
  + Danh sách sinh viên Trung bình
- Hiển thị biểu đồ:
  + Biểu đồ cột thống kê học lực
  + Biểu đồ phân cụm K-Means
  + Biểu đồ tròn tỷ lệ học lực
- Xuất file:
  + KetQua_XepLoai_GPA.xlsx
  + bieu_do_cot.png
  + bieu_do_kmeans.png
  + bieu_do_tron.png

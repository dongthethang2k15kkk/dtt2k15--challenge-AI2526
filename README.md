# Python Challenge Week

Notebook tự học Python này được thiết kế cho "Python Challenge Week" tại BK-AUTO. Bạn sẽ đi từ kiến thức nền tảng, luyện tập với các ví dụ thực tế cho tới triển khai dự án dữ liệu hoàn chỉnh.

## Mục lục

- [Python Challenge Week](#python-challenge-week)
  - [Mục lục](#mục-lục)
  - [Giới thiệu](#giới-thiệu)
  - [Nội dung Repository](#nội-dung-repository)
  - [Quy trình GitHub \& Google Colab](#quy-trình-github--google-colab)
    - [Chuẩn bị repository](#chuẩn-bị-repository)
    - [Làm việc trên Google Colab](#làm-việc-trên-google-colab)
    - [Thói quen commit đề xuất](#thói-quen-commit-đề-xuất)
  - [Cách sử dụng notebook](#cách-sử-dụng-notebook)
  - [Lộ trình module](#lộ-trình-module)
  - [Dự án cuối khóa](#dự-án-cuối-khóa)
  - [Gợi ý tiếp theo](#gợi-ý-tiếp-theo)

## Giới thiệu

`python_challenge_week.ipynb` tổng hợp toàn bộ outline tuần thử thách:

- **Phần Setup**: Giới thiệu challenge, hướng dẫn cài `numpy` và `matplotlib`.
- **Phần 1 – Python Essentials**: 6 module về cú pháp cơ bản, cấu trúc dữ liệu, vòng lặp, hàm, xử lý ngoại lệ.
- **Phần 2 – Python for Data Science**: 3 module về list comprehension, thống kê và NumPy.
- **Phần 3 – Data Visualization**: Làm quen matplotlib.
- **Phần 4 – Final Projects**: 3 dự án tổng hợp để bạn vận dụng toàn bộ kỹ năng.

## Nội dung Repository

| Tệp | Mục đích |
| --- | --- |
| `python_challenge_week.ipynb` | Notebook chính chứa nội dung học tập, ví dụ, bài tập và skeleton dự án. |

## Quy trình GitHub & Google Colab

### Chuẩn bị repository

1. Truy cập repo gốc: `https://github.com/Challengeweek-AI-BK-AUTO/meomeo-challenge-AI2526`.
2. Nhấn **Fork** và chọn tổ chức Challengeweek-AI-BK-AUTO.
3. Đặt lại tên repo khi fork: thay tiền tố `meomeo` bằng của bạn ví dụ `tenban-challenge-AI2526`.
4. Kiểm tra lại quyền truy cập, thiết lập branch mặc định và bật bảo vệ nhánh (nếu cần) trước khi bắt đầu.

### Làm việc trên Google Colab

1. Mở file `python_challenge_week.ipynb` trên GitHub trong repo mới của bạn.
2. Sử dụng nút **Open in Colab** (nếu đã cài tiện ích) hoặc đổi URL theo mẫu `https://colab.research.google.com/github/<org>/<repo>/blob/<branch>/python_challenge_week.ipynb` để mở trực tiếp trên Colab.
3. Trong Colab, đảm bảo bạn đã đăng nhập cùng tài khoản Google có quyền truy cập GitHub.
4. Khi bắt đầu chỉnh sửa, chọn **File ▸ Save a copy in GitHub…** (Lưu bản sao vào GitHub) hoặc bấm Ctrl + S, chọn repo fork của bạn, nhánh mong muốn và điền thông điệp commit.
5. Lặp lại thao tác “Save a copy in GitHub” sau mỗi lần cập nhật để lưu lịch sử làm việc. Colab sẽ tự động tạo commit mới với nội dung bạn đã chỉnh sửa.

### Thói quen commit đề xuất

- Tạo commit nhỏ sau từng module hoặc thử thách để dễ dàng theo dõi tiến độ.
- Sử dụng thông điệp commit mô tả rõ thay đổi, ví dụ `feat: hoan thanh module 2`.
- Khi làm việc nhóm, thống nhất quy tắc đặt tên branch và quy trình review Pull Request trước khi merge.

## Cách sử dụng notebook

1. Mở notebook bằng Colab(khuyến dụng), VS Code hoặc `jupyter notebook`.
2. Chạy cell cài đặt `%pip install --quiet numpy matplotlib` (chỉ cần một lần).
3. Thực thi cell kiểm tra import để đảm bảo thư viện đã sẵn sàng.
4. Với mỗi module:
	- Đọc phần 📖 Giải thích.
	- Chạy cell 💻 Ví dụ.
	- Ghi chú ⚠️ Common Mistakes và 💡 Pythonic Way.
	- Hoàn thành cell 🎯 Thử thách (các dòng TODO).
5. Ở cuối notebook, chọn một dự án và hoàn thiện skeleton được cung cấp.

## Lộ trình module

| Module | Chủ đề | Điểm nhấn |
| --- | --- | --- |
| 1. Basic Syntax & Data Types | Kiểu dữ liệu, ép kiểu, f-string | Tính BMI |
| 2. List | List mutable, slicing | Thống kê điểm |
| 3. Dictionary | Key-value, dict.get | Đếm tần suất từ |
| 4. Control Flow | if/elif/else, for, while | Bảng cửu chương |
| 5. Functions & Strings | Định nghĩa hàm, docstring | Kiểm tra palindrome |
| 6. Exception Handling | try/except, EAFP | Validate số nguyên dương |
| 7. List Comprehension & Lambda | Comprehension vs map/filter | Bình phương số chẵn |
| 8. Statistics & Math | `statistics` module | Mean/median/std |
| 9. NumPy Basics | Vector hoá, broadcasting | Chuẩn hoá điểm |
| 10. Matplotlib Basics | plot, bar, hist, scatter | Histogram phân bố điểm |

## Dự án cuối khóa

1. **Quản lý điểm học sinh (Nâng cao)** – tổ chức dữ liệu bằng dict, tính thống kê, vẽ histogram và bar chart.
2. **Vẽ hình thoi** – luyện kỹ năng vòng lặp, xử lý ngoại lệ, thao tác chuỗi.
3. **Statistical Analysis Project ⭐** – phân tích nhiều môn học với NumPy, thống kê và trực quan hoá.

## Gợi ý tiếp theo

- Lưu ý commit kết quả sau mỗi module để theo dõi tiến độ.
- Thử mở rộng bài toán hoặc thêm tập dữ liệu mới cho các dự án để hiểu sâu hơn.
- Nếu làm việc nhóm, phân chia module/dự án để thảo luận hiệu quả.

Made by [Viet Anh Pham](https://github.com/vanhpham) with supported from ChatGPT
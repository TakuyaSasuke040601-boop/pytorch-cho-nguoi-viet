\# 🤝 Hướng dẫn đóng góp | PyTorch cho người Việt



\*\*Đọc file này trước khi code dòng đầu tiên.\*\* 5 phút đọc = Tiết kiệm 5 giờ debug cho cả team.





\## 🎯 Nguyên tắc vàng của Team Trail Blazer



1\. \*Viết cho sinh viên Cần Thơ đọc hiểu, không viết cho GK đọc.\* Nếu mẹ bạn không hiểu bạn đang làm gì, viết lại.

2\. \*1 PR = 1 việc nhỏ.\* PR 500 dòng code = reject. PR 50 dòng + docs = merge ngay.

3\. \*Commit message phải kể chuyện.\* fix bug = tệ. docs: thêm ảnh lỗi thường gặp khi cài torch trên Win7 = merge liền.



\## ⚡ Setup 5 phút cho thành viên mới



```bash

\# 1. Fork repo này về GitHub của bạn

\# 2. Clone về máy

git clone https://github.com/\[username-của-bạn]/pytorch-cho-nguoi-viet.git

cd pytorch-cho-nguoi-viet



\# 3. Tạo nhánh mới - đặt tên theo việc bạn làm

git checkout -b docs/them-huong-dan-cai-win7



\# 4. Cài môi trường

pip install -r requirements.txt



\# 5. Chạy test - phải xanh mới được push

python -m pytest tests/


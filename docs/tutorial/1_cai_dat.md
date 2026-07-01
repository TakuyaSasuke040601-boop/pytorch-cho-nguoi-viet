\# Bài 1: Cài PyTorch 5 phút cho máy yếu - Không cần biết tiếng Anh



\*\*Dành cho:\*\* Sinh viên năm 1, máy 4GB RAM, Win 7/10, mạng 3G  

\*\*Kết quả:\*\* Chạy được dòng `import torch` không báo lỗi





## Bước 1: Tải Python - Giống tải Zalo



1\. Vào link: https://www.python.org/downloads/

2\. Bấm nút vàng "Download Python 3.11"  

&#x20;  \[Chỗ này chèn ảnh chụp màn hình]

3\. Mở file vừa tải → \*QUAN TRỌNG: Tick vào ô "Add Python to PATH"\*  

&#x20;  \[Chỗ này chèn ảnh chụp màn hình]

4\. Bấm Install Now → Đợi 2 phút



## Bước 2: Cài PyTorch - Copy 1 dòng là xong



1\. Bấm nút Windows + R → Gõ cmd → Enter

2\. Màn hình đen hiện lên, copy dòng này paste vào rồi Enter:

```
pip install torch torchvision torchaudio '''index-url https://download.pytorch.org/whl/cpu
```

3. Đợi 5 phút. Thấy chữ Successfully installed torch là xong.  

&#x20;  \[Chỗ này chèn ảnh chụp màn hình]



## Bước 3: Test - Chắc chắn 100% thành công



1\. Vẫn ở màn hình đen, gõ python → Enter

2\. Gõ tiếp import torch → Enter. Không báo đỏ là thắng.

3\. Gõ print(torch.\_\_version\_\_) → Enter. Nó hiện 2.3.0 là xong.



\*Bị lỗi?\* Chụp màn hình lỗi + đăng vào Issue #1. Team rep trong 1 giờ.



\*Làm được rồi?\* Comment "Em ở ĐH Cần Thơ, máy em Win7 4GB chạy được rồi ạ" vào Issue #1 để team có động lực làm tiếp.



\---

\*Bài tiếp theo:\* Bài 2 - Tensor đầu tiên, giống như ô Excel nhưng AI hiểu được


# Face Recognition

## Giới thiệu

Dự án **Face Recognition** là một ứng dụng nhận diện khuôn mặt sử dụng các kỹ thuật xử lý ảnh và học máy. Dự án nhằm mục đích nhận diện và xác minh danh tính từ hình ảnh hoặc video trong thời gian thực.

## Tính năng

- Nhận diện khuôn mặt từ hình ảnh hoặc webcam.
- Lưu trữ và so sánh dữ liệu khuôn mặt.
- Hỗ trợ giao diện dòng lệnh đơn giản.

## Công nghệ sử dụng

- **Python 3.7+**
- **OpenCV**: Xử lý hình ảnh.
- **dlib**: Nhận diện và mã hóa khuôn mặt.
- **NumPy**: Xử lý dữ liệu số.

## Cài đặt

### Yêu cầu
- Python 3.7 trở lên.
- Webcam (nếu sử dụng nhận diện thời gian thực).
- pip để cài đặt thư viện.

### Hướng dẫn

1. **Clone repository**:
   ```bash
   git clone https://github.com/Lochke/Face-Recognition.git
   cd Face-Recognition
   ```

2. **Tạo môi trường ảo**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. **Cài đặt thư viện**:
   ```bash
   pip install -r requirements.txt
   ```

## Sử dụng

1. **Chuẩn bị dữ liệu**:
   - Thêm hình ảnh khuôn mặt vào thư mục `dataset/` (theo định dạng: `tên_người.jpg`).
   - Chạy script để mã hóa khuôn mặt:
     ```bash
     python encode_faces.py
     ```

2. **Chạy nhận diện**:
   ```bash
   python recognize_faces.py
   ```
   - Mở webcam hoặc cung cấp đường dẫn hình ảnh để nhận diện.

## Cấu trúc thư mục

```
Face-Recognition/
├── dataset/                # Hình ảnh khuôn mặt
├── encodings/              # Dữ liệu mã hóa khuôn mặt
├── encode_faces.py        # Script mã hóa khuôn mặt
├── recognize_faces.py遵照以下步骤操作：

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Giấy phép

Dự án được phát hành dưới [Giấy phép MIT](LICENSE).

## Liên hệ

- Tác giả: Lochke
- GitHub: [https://github.com/Lochke](https://github.com/Lochke)

---

### Hướng dẫn lưu tệp README
1. Tạo một tệp mới trong thư mục dự án với tên `README.md`.
2. Sao chép và dán nội dung trên vào tệp.
3. Lưu tệp và commit lên repository:
   ```bash
   git add README.md
   git commit -m "Thêm tệp README"
   git push origin main
   ```

### Ghi chú
- README này giả định dự án sử dụng Python, OpenCV, và dlib, phù hợp với các dự án nhận diện khuôn mặt phổ biến.

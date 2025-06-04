# NhapMonXuLyAnhSo
Đoạn mã Python bạn cung cấp sử dụng các **công nghệ và thư viện xử lý ảnh và hiển thị hình ảnh**. Cụ thể:

---

### 📌 **Công nghệ và thư viện sử dụng:**

1. **OpenCV (`cv2`)** – Thư viện mã nguồn mở mạnh mẽ cho **xử lý ảnh và thị giác máy tính**:

   * `cv2.imread(...)`: Đọc ảnh từ file.
   * `cv2.cvtColor(...)`: Chuyển đổi không gian màu (ở đây là từ BGR sang RGB).
   * `cv2.blur(...)`: Áp dụng bộ lọc làm mờ ảnh (mean filter), một kỹ thuật xử lý ảnh cơ bản.

2. **Matplotlib (`matplotlib.pyplot`)** – Thư viện vẽ đồ thị dùng để **hiển thị ảnh hoặc biểu đồ**:

   * `plt.imshow(...)`: Hiển thị ảnh trong không gian RGB.
   * `plt.subplot(...)`: Chia khung hiển thị để vẽ nhiều ảnh cùng lúc.
   * `plt.title(...)`: Gán tiêu đề cho ảnh.
   * `plt.show()`: Hiển thị tất cả ảnh đã vẽ.

---

### 🧠 **Công nghệ nền tảng và kỹ thuật liên quan:**

* **Xử lý ảnh số (Digital Image Processing)**: Mean Filter là một kỹ thuật xử lý ảnh dùng để làm mờ ảnh, giảm nhiễu.
* **Thị giác máy tính (Computer Vision)**: Các thao tác như đọc ảnh, chuyển đổi không gian màu, làm mờ ảnh là một phần cơ bản trong thị giác máy tính.
* **Trực quan hóa dữ liệu (Data Visualization)**: Sử dụng `matplotlib` để hiển thị trực quan ảnh giúp phân tích hiệu quả hơn.

---

### ✅ Tóm lại:

* **Công nghệ chính**: Xử lý ảnh số, thị giác máy tính.
* **Thư viện sử dụng**: OpenCV (cv2), Matplotlib.
* **Ứng dụng**: Làm mờ ảnh bằng mean filter, hiển thị kết quả so sánh giữa ảnh gốc và ảnh đã xử lý.

Nếu bạn cần mở rộng đoạn code này sang các bộ lọc khác như median, Gaussian hoặc edge detection (Canny, Sobel), mình có thể hỗ trợ thêm.

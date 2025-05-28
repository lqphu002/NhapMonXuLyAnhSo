# NhapMonXuLyAnhSo
Lab1:
Công nghệ sử dụng
1. Ngôn ngữ lập trình
Python: Ngôn ngữ lập trình cấp cao, phổ biến trong lĩnh vực AI, Machine Learning và xử lý ảnh nhờ tính đơn giản và hệ sinh thái thư viện mạnh mẽ.
2. Thư viện sử dụng
a. OpenCV (Open Source Computer Vision Library)
Chức năng: Thư viện mã nguồn mở mạnh mẽ dùng để xử lý ảnh và video theo thời gian thực.
Sử dụng trong mã:
Đọc ảnh: cv2.imread()
Tách/ghép kênh màu: cv2.split(), cv2.merge()
Chuyển đổi không gian màu: cv2.cvtColor()
Lưu ảnh: cv2.imwrite()
b. NumPy
Chức năng: Thư viện xử lý mảng đa chiều (ndarray), rất nhanh và hiệu quả.
Sử dụng trong mã:
Tạo ma trận rỗng (ảnh đen): np.zeros_like()
Thao tác với các kênh màu bằng indexing: image[:, :, [0, 2, 1]]
c. Matplotlib
Chức năng: Thư viện dùng để trực quan hóa dữ liệu, đặc biệt là hiển thị ảnh và đồ thị.
Sử dụng trong mã:
Hiển thị ảnh: plt.imshow()
Bố trí subplot và tiêu đề: plt.subplot(), plt.title(), plt.tight_layout(), plt.axis("off"), plt.show()
3. Kỹ thuật xử lý ảnh sử dụng
Kỹ thuật:
Tách kênh màu (Channel Splitting)	
Ghép kênh (Channel Merging)	
Hoán đổi kênh màu (Channel Swapping)	
Chuyển đổi không gian màu	
Giải thích:
Tách ảnh màu thành 3 kênh R, G, B riêng biệt.
Tạo ảnh chỉ chứa một kênh màu bằng cách giữ lại một kênh và làm đen 2 kênh còn lại.
Đổi vị trí các kênh màu để tạo ra hiệu ứng ảnh khác biệt hoặc thử nghiệm.
Từ BGR sang RGB để tương thích với Matplotlib.
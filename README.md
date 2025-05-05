# Đề tài: Hệ thống Gợi ý Chuyên ngành cho Sinh viên dựa trên Khai phá Dữ liệu

## 🔍 Giới thiệu

Trong bối cảnh sinh viên đại học thường gặp khó khăn khi chọn chuyên ngành phù hợp, nhóm nghiên cứu đã triển khai đề tài **"Xây dựng kho dữ liệu về đặc điểm môn học và điểm số của sinh viên – Khai phá dữ liệu để gợi ý chọn chuyên ngành"**. Mục tiêu là phát triển một hệ thống có khả năng đề xuất chuyên ngành phù hợp với năng lực học tập và sở thích của sinh viên thông qua các kỹ thuật phân tích và học máy hiện đại.

## 🎯 Mục tiêu

- **Xây dựng kho dữ liệu** lưu trữ thông tin về sinh viên, môn học, điểm số, kỹ năng và loại môn.
- **Khai phá dữ liệu** nhằm phát hiện các mẫu và xu hướng học tập gắn liền với chuyên ngành.
- **Phát triển hệ thống gợi ý** chuyên ngành dựa trên dữ liệu và các thuật toán học máy như Logistic Regression, KNN, Random Forest, Neural Network.

## 🛠 Công nghệ sử dụng

- **Ngôn ngữ**: Python
- **Thư viện học máy**: Scikit-learn, Pandas, NumPy
- **Trực quan hóa**: Matplotlib, Seaborn
- **Web framework**: Flask
- **Giao diện người dùng**: HTML, CSS, JavaScript
- **Cơ sở dữ liệu**: MySQL

## ⚙️ Quy trình chính

1. **Tiền xử lý dữ liệu**: Làm sạch, chuẩn hóa dữ liệu, kiểm tra thiếu/ngoại lệ/trùng lặp.
2. **Phân tích đặc trưng**: Phân loại môn học (core/general), phân tích điểm trung bình, kỹ năng.
3. **Huấn luyện mô hình**: Áp dụng các thuật toán phân loại và tìm tham số tối ưu bằng GridSearchCV.
4. **Triển khai hệ thống web**: Giao diện nhập điểm, dự đoán chuyên ngành, hiển thị kết quả phù hợp.

## 🧠 Thuật toán triển khai

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Neural Network (MLPClassifier)

## 🖥 Giao diện hệ thống

- Trang chủ hiển thị các trường hợp mẫu.
- Trang nhập điểm để sinh viên tự dự đoán chuyên ngành.
- Giao diện kết quả thể hiện mức độ phù hợp với từng chuyên ngành, kỹ năng cần cải thiện và gợi ý học phần.

## 📈 Kết quả & Ý nghĩa

- Độ chính xác cao đối với sinh viên đã học đầy đủ môn học.
- Hệ thống giúp sinh viên có định hướng tốt hơn trong việc chọn chuyên ngành.
- Hỗ trợ giảng viên và nhà trường trong việc tư vấn và điều chỉnh chương trình học.

## 🚧 Hạn chế và đề xuất

- Hiện hệ thống mới sử dụng dữ liệu điểm số, cần bổ sung thêm yếu tố định tính (tính cách, sở thích).
- Dữ liệu vẫn còn nhỏ, cần mở rộng tập dữ liệu để cải thiện độ chính xác mô hình.
- Cần thu thập thêm phản hồi người dùng để cải tiến thuật toán.

## 👨‍💻 Nhóm thực hiện

Nhóm sinh viên từ Học viện Công nghệ Bưu chính Viễn thông – Khoa CNTT.

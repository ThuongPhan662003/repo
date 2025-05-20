# 📘 Tóm tắt báo cáo nhóm 5

**Đề tài**: **Xây dựng kho dữ liệu dựa trên đặc điểm môn học, điểm số sinh viên và khai phá để gợi ý chuyên ngành**

## 1. Giới thiệu đề tài

Mục tiêu là xây dựng kho dữ liệu các đặc trưng học tập (điểm, kỹ năng, phân loại môn) và áp dụng thuật toán khai phá để gợi ý 1 trong 3 chuyên ngành:

- Công nghệ phần mềm
- An toàn thông tin
- Trí tuệ nhân tạo

## 2. Thành phần dữ liệu

- Thông tin sinh viên: `student_id`, `gpa`, `current_semester`
- Môn học: `subject_name`, `subject_type`, `credits`, `hours`, `skills`
- Điểm số: `final_grade`, `midterm`, `attendance`, `assignment`, `retake_count`
- Kỹ năng: danh sách kỹ năng sinh viên học được từ môn học

## 3. Các bước xử lý dữ liệu

- Làm sạch, kiểm tra thiếu/trùng/ngoại lai
- Xử lý outlier bằng phương pháp capping
- Phân tích tương quan giữa các biến điểm
- Xử lý kỹ năng thành đặc trưng (vector kỹ năng)
- Rời rạc hóa điểm để thực hiện chi-square test

## 4. Mô hình và đánh giá

- Áp dụng các mô hình: Logistic Regression, KNN, Random Forest, Neural Network
- Logistic Regression cho kết quả tốt nhất: **Accuracy ≈ 98.0%**
- Sử dụng GridSearchCV để tìm tham số tốt nhất
- Triển khai giao diện web dự đoán chuyên ngành dựa vào điểm nhập vào

## 5. Một số hình ảnh minh hoạ

![Hình 14: Phân bố chuyên ngành] (./images/image.png)
![Hình 38: So sánh mô hình] (./images/image1.png)
![Hình 42: Giao diện dự đoán] (./images/image2.png)

## 6. Kết luận

- Mô hình Logistic Regression có hiệu quả cao trong phân loại chuyên ngành.
- Điểm cuối kỳ (final_grade) có ảnh hưởng lớn nhất đến chuyên ngành được chọn.
- Giao diện web giúp sinh viên nhập điểm và nhận gợi ý chuyên ngành trực quan.

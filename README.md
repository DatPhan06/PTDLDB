# Dự án Phân Tích Dữ Liệu Khách Hàng Ngân Hàng - Dự Đoán Rời Bỏ

## Mô tả dự án

Dự án này được phát triển để giải quyết vấn đề dự đoán khách hàng rời bỏ dịch vụ ngân hàng bằng cách sử dụng các kỹ thuật học máy. Chúng tôi áp dụng phương pháp cân bằng dữ liệu với SMOTE và các thuật toán học máy tổ hợp như Random Forest và Gradient Boosting để đạt hiệu suất dự đoán cao nhất. Ngoài ra, giá trị Shapley được sử dụng để giải thích mô hình và phân tích tầm quan trọng của các đặc trưng.

## Các bước thực hiện

1. **Tiền xử lý dữ liệu**:

   - Mã hóa các biến danh mục bằng phương pháp One-Hot Encoding.
   - Sử dụng phương pháp SMOTE để cân bằng dữ liệu giữa các lớp.
   - Chuẩn hóa dữ liệu để mô hình học hiệu quả hơn.

2. **Mô hình hóa**:

   - Thử nghiệm các mô hình như Random Forest, Gradient Boosting, Decision Trees, và Naive Bayes.
   - Sử dụng GridSearchCV để tối ưu hóa tham số.

3. **Đánh giá mô hình**:
   - Sử dụng các chỉ số như accuracy, F1-score và AUC để đánh giá mô hình.
   - Phân tích tầm quan trọng của các đặc trưng và giá trị Shapley để giải thích kết quả mô hình.

## Hướng dẫn cài đặt

1. Clone repository này:
   ```bash
   git clone https://github.com/DatPhan06/PTDLDB
   ```
2. Cài đặt các thư viện yêu cầu:
   ```bash
   pip install -r requirements.txt
   ```
3. Chạy notebook để huấn luyện và đánh giá mô hình:
   ```bash
    jupyter notebook ./ptdldb.ipynb
   ```

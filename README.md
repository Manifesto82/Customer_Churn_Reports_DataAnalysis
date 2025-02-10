# Customer Churn Analysis Project
# Mục tiêu

Mục tiêu của dự án là xây dựng một mô hình dự đoán tỷ lệ khách hàng hủy dịch vụ mạng và phân tích các giải pháp để giữ chân khách hàng. Dự án sử dụng bộ dữ liệu chứa thông tin về khách hàng, bao gồm các dịch vụ họ đăng ký và biến mục tiêu Churn (khách hàng có hủy dịch vụ hay không).

# Dữ liệu

Bộ dữ liệu: Chứa các thông tin cơ bản về khách hàng như customerID, gender, SeniorCitizen, Partner, Dependents, tenure, PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges, và Churn.

Biến mục tiêu: Churn (1: Khách hàng hủy dịch vụ, 0: Khách hàng không hủy dịch vụ).
# Tiền xử lý dữ liệu
Dữ liệu ban đầu chủ yếu ở dạng object, nên đã được chuyển đổi sang dạng số để thuận tiện cho việc phân tích.

Các bước tiền xử lý bao gồm:
Chuyển đổi các giá trị categorical sang dạng số.

Kiểm tra và xử lý các giá trị đặc biệt.

Đếm số lượng giá trị riêng biệt trong từng cột.
# Các thuật toán sử dụng

Logistic Regression:

Chia dữ liệu thành tập huấn luyện (70%) và tập kiểm tra (30%).

Huấn luyện mô hình và tính toán độ chính xác (accuracy).

Sử dụng Confusion Matrix và Classification Report để đánh giá hiệu suất mô hình.

Support Vector Machine (SVM):

Sử dụng kernel tuyến tính và các tham số C=10, Gamma=1.

Huấn luyện mô hình và tính toán độ chính xác.

Đánh giá mô hình thông qua Confusion Matrix và Classification Report.

# Đề tài cuối kỳ môn Phân tích Khai phá Dữ liệu
### 1. Giới thiệu đề tài
Đề tài sử dụng hai bộ dữ liệu Android Malware và Cybersecurity Intrusion để nghiên cứu các phương pháp phát hiện mối đe dọa an ninh mạng. Bộ dữ liệu Android Malware tập trung vào việc nhận diện ứng dụng độc hại trên nền tảng Android, trong khi Cybersecurity Intrusion hỗ trợ phát hiện các hành vi xâm nhập mạng bất thường. Các bài toán chính bao gồm phân lớp nhằm phân lớp mã độc và lưu lượng tấn công, phân cụm để khám phá các nhóm hành vi tương đồng, và khai phá luật kết hợp để tìm ra các đặc trưng hoặc mẫu xuất hiện thường xuyên trong dữ liệu. Ngoài ra, đề tài còn thực hiện phân tích đặc trưng và trực quan hóa dữ liệu nhằm hỗ trợ đánh giá và cải thiện hiệu quả mô hình.

### 2. Dataset được sử dụng trong đề tài
- Dataset Android Malware: https://www.kaggle.com/datasets/subhajournal/android-malware-detection
- Dataset Cybersecurity Intrusion: https://www.kaggle.com/datasets/dnkumars/cybersecurity-intrusion-detection-dataset

### 3. Cấu trúc thư mục đề tài 

source
├───AndroidMalware
│   ├───clustering
│   │       clustering.ipynb
│   │
│   ├───data_processed
│   │       cleaned_data.parquet
│   │       x_test.parquet
│   │       x_train.parquet
│   │       x_val.parquet
│   │       y_test.parquet
│   │       y_train.parquet
│   │       y_val.parquet
│   │
│   ├───data_splitting
│   │       data_splitting.ipynb
│   │
│   ├───eda
│   │       eda.ipynb
│   │
│   ├───features
│   │       features.ipynb
│   │
│   ├───model
│   │       model.ipynb
│   ├───preprocess
│   │       preprocess.ipynb
│   │
│   └───test
│           test.ipynb
│
└───CybersecurityIntrusion
    │
    │
    ├───features
    │       features.ipynb
    │
    ├───notebook
    │       eda1.ipynb
    │
    ├───preprocess
    │       preprocess.ipynb
    │
    ├───rules
    │       rules.ipynb
    │       rules2.ipynb
    │       rules3.ipynb
    │       rules4.ipynb
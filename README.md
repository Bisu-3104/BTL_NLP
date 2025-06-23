# BTL_NLP

# 🧠 Ứng Dụng Mô Hình Vector Space Model Và BERT Trong Việc Truy Vấn Thông Tin Câu Hỏi

## 📌 Giới thiệu

Đề tài này nhằm xây dựng và so sánh hai mô hình truy xuất thông tin:

- **Vector Space Model (VSM)** với biểu diễn Bag-of-Words và đo độ tương đồng cosine.
- **BERT (Bidirectional Encoder Representations from Transformers)** cho tìm kiếm ngữ nghĩa sâu.

Bài toán đặt ra: Trả về các đoạn văn bản phù hợp nhất với một truy vấn câu hỏi đầu vào, từ tập dữ liệu MS MARCO.

---

## 📁 Cấu trúc thư mục
- ├── Data/ # Dữ liệu đầu vào (MS MARCO)
- ├── Code/ # Triển khai mô hình
- ├── Report/ # Báo cáo kết 
- ├── README.md # Tài liệu mô tả repo
- └── requirements.txt # Các thư viện cần thiết

## 🔍 Các Bước Tiền xử lý
Các bước áp dụng:
- Chuyển lowercase
- Loại bỏ dấu câu và ký tự đặc biệt
- Tokenization
- Stopword Removal
- Porter Stemming (cho VSM)

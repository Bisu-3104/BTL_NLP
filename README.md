# BTL_NLP

# 🧠 Ứng dụng Mô hình Vector Space Model và BERT trong Truy Vấn Thông Tin

## 📌 Giới thiệu

Đề tài này nhằm xây dựng và so sánh hai mô hình truy xuất thông tin:

- **Vector Space Model (VSM)** với biểu diễn Bag-of-Words và đo độ tương đồng cosine.
- **BERT (Bidirectional Encoder Representations from Transformers)** cho tìm kiếm ngữ nghĩa sâu.

Bài toán đặt ra: Trả về các đoạn văn bản phù hợp nhất với một truy vấn câu hỏi đầu vào, từ tập dữ liệu MS MARCO.

---

## 📁 Cấu trúc thư mục
- ├── data/ # Dữ liệu đầu vào (MS MARCO)
- ├── models/ # Triển khai mô hình
- ├── Report/ # Báo cáo kết 
- ├── README.md # Tài liệu mô tả repo
- └── requirements.txt # Các thư viện cần thiết

## 🔍 Tiền xử lý
Các bước áp dụng:
-Chuyển lowercase
- Loại bỏ dấu câu và ký tự đặc biệt
- Tokenization
- Stopword Removal
- Porter Stemming (cho VSM)

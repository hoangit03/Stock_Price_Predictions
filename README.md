# 📈 Stock Price Prediction using LSTM

Dự án này sử dụng mạng LSTM (Long Short-Term Memory) để dự đoán giá đóng cửa cổ phiếu dựa trên dữ liệu lịch sử. Mô hình học sâu được huấn luyện bằng dữ liệu từ Yahoo Finance.

## 🧠 Mục tiêu
- Dự đoán giá đóng cửa (Close Price) trong tương lai của một mã cổ phiếu cụ thể.
- Trực quan hóa kết quả dự đoán so với giá thực tế.

## 📂 Cấu trúc thư mục
```
├── Stock_Predictions.ipynb     # File notebook chính
├── README.md                   # File mô tả dự án
├── requirements                # File thư viện cần thiết
```
## 🛠️ Công nghệ sử dụng

- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib
- scikit-learn
- TensorFlow / Keras
- yfinance

## 📊 Dữ liệu đầu vào

Dữ liệu được lấy tự động từ [Yahoo Finance](https://finance.yahoo.com) thông qua thư viện `yfinance`.

- **Ticker**: Mã cổ phiếu (FPT, MSN, PNJ, VIC)
- **Thời gian**: 2018-2024

## 🚀 Cách chạy dự án

1. **Cài đặt thư viện cần thiết**
   ```bash
   pip install -r requirements.txt
   ```

2. **Chạy notebook**
   - Mở `Stock_Predictions.ipynb` bằng Jupyter Notebook hoặc VSCode.
   - Chạy lần lượt từng ô (cell).

## 📈 Mô hình

- Mô hình sử dụng mạng **LSTM** với nhiều tầng để học đặc trưng chuỗi thời gian.
- Dữ liệu được chuẩn hóa và chia thành tập huấn luyện và kiểm tra.
- Mô hình dự đoán giá đóng cửa của cổ phiếu trong tương lai dựa trên 60 ngày gần nhất.

## 📷 kết quả
Mô hình trực quan hóa giá dự đoán và giá thực tế bằng biểu đồ:


## 📌 Ghi chú
- Dự án mang tính học thuật, không sử dụng cho mục đích đầu tư thực tế.
- Kết quả có thể khác nhau tùy vào mã cổ phiếu, khoảng thời gian và tham số huấn luyện.

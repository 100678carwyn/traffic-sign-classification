# traffic-sign-classification

# Traffic Signs Dataset

## 1. Giới thiệu
Dataset này là bản đã được xử lý của bộ dữ liệu German Traffic Sign Recognition Benchmark (GTSRB) — một bộ ảnh nhiều lớp biển báo giao thông từ Đức với **43 lớp khác nhau**.  
Bộ dữ liệu này đã được chuẩn hóa, tiện sử dụng cho việc huấn luyện mạng nơ‑ron phân loại ảnh.

## 2. Nguồn tải
Bạn có thể tải tập dữ liệu từ đường link sau:  
[Download Traffic Signs Dataset](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip)

## 3. Cấu trúc dữ liệu sau khi giải nén
Sau khi giải nén `traffic-signs-data.zip`, thư mục sẽ chứa các file:
- `train.p` – tập huấn luyện (features + labels)  
- `valid.p` – tập validation  
- `test.p`  – tập kiểm tra  

Mỗi file là một pickle (Python) với cấu trúc:
```python
{
  "features": array([...], dtype=np.uint8 or float64),
  "labels":   array([...], dtype=np.int64)
}
## References / Credits
- Tutorial code tham khảo từ PyImageSearch: [Traffic Sign Classification with Keras](https://www.pyimagesearch.com/2019/11/04/traffic-sign-classification-with-keras-and-deep-learning/)
- Dataset: German Traffic Sign Recognition Benchmark (GTSRB) - [https://benchmark.ini.rub.de/gtsrb_dataset.html](https://benchmark.ini.rub.de/gtsrb_dataset.html)

<div align="center">
    <h1>Breast cancer patient prediction</h1>
</div>

## 📌 Mô tả
Dự đoán khối u ác tính hay lành tính sử dụng data streaming với Apache Spark và học máy (Logistic Regression).

## Cách chạy
* **stream data**: ```python src/stream.py --file-path datasets/breast-cancer.csv --batch-size 50```
* **train, predict and evalute model after recieving data**: ```python src/main.py ```

FROM python:3.11-slim
# 設定工作目錄
WORKDIR /app

# 複製本機檔案到容器內
COPY requirements.txt ./

# 安裝所需的 Python 套件
RUN pip install --no-cache-dir -r requirements.txt

# 複製應用程式程式碼
COPY . .
CMD ["python", "main.py"]

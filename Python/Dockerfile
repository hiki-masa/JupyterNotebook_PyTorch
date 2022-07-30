FROM python:3.10

RUN apt-get update && \
    pip install --upgrade pip && \
	apt install -y python3-pip
# Jupyter Notebookのインストール
RUN pip install notebook
# PyTorchのインストール
RUN pip3 install torch==1.11.0 torchvision==0.12.0 torchaudio==0.11.0
# その他必要なライブラリのインストール
RUN pip install numpy==1.22.0 && \
    pip install matplotlib==3.5.0 && \
    pip install pandas==1.4.0 && \
    pip install lime

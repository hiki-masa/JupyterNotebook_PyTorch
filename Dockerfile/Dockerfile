FROM python:3.10

RUN apt update && \
	apt install -y python3-pip

# Jupyter Notebookのインストール
RUN pip install notebook && \
    pip install ipywidgets

# パッケージ一括インストール
COPY requirements.txt .
RUN pip3 install -r requirements.txt

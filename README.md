# Umanohone

## Description
- 準備中

## Getting Started
1. dockerの実行環境を準備
1. `docker-compose up` で tensorflow + jupyternotebook を起動
1. jupyter notebookへのアクセス方法
    1. 起動時に以下のようなログが流れる
        ```
        umanohone-tensorflow-1  |     To access the notebook, open this file in a browser:
        umanohone-tensorflow-1  |         file:///root/.local/share/jupyter/runtime/nbserver-1-open.html
        umanohone-tensorflow-1  |     Or copy and paste one of these URLs:
        umanohone-tensorflow-1  |         http://xxxxxxxxx:8888/?token=6fbbxxxxxxxx
        ```
        `token=`以降の文字列をコピー
    1. `http://localhost:8001/` にアクセスして、1.でコピーしたtokenをコピペしてログイン

1. サンプルコードの実行方法
    1. `docker-compose tensorflow bash`
    1. `python notebooks/sample.py`

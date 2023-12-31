# image-upload-with-process
演習講義の課題サンプル

画像のアップロードを行うWebインターフェイスと、アップロードされた画像のファイル変更を検知して画像処理を行う画像処理プログラムを組み合わせたシステムの構築

## Initial Setting

```zsh
$ git clone https://github.com/2023AIT-OOP2-G00/image-upload-with-process.git
$ cd image-upload-with-process
$ python -m venv .env
$ source .env/bin/activate
(.env) $ pip install -r requirements.txt
```

## Require

- Python version : 3.10 or higher
- OpenCV version : 4.8.1 or higher

```
Flask==3.0.0
opencv-python==4.8.1.78
watchdog==3.0.0
```

## Usage

このシステムは、演習の都合上Webインターフェイスと画像処理プログラムを別個で起動する必要があります。

### Webインターフェイスの起動

```zsh
$ source .env/bin/activate
(.env) $ python web.py
```

### 画像処理プログラムの起動

```zsh
$ source .env/bin/activate
(.env) $ python image_process.py
```

# fast-api-practice

## 必要パッケージのインストール
```
$ source env_api/bin/activate
(env_api) fast_api $ pip install fastapi==0.70.0
(env_api) fast_api $ pip install uvicorn==0.14.0
(env_api) fast_api $ pip install fastapi_csrf_protect==0.2.1
(env_api) fast_api $ pip install motor==2.5.1
(env_api) fast_api $ pip install PyJWT==2.3.0
(env_api) fast_api $ pip install passlib==1.7.4
(env_api) fast_api $ pip install python-decouple==3.3
(env_api) fast_api $ pip install pymongo==3.12.1
(env_api) fast_api $ pip install dnspython==2.1.0
(env_api) fast_api $ pip install gunicorn==20.1.0
(env_api) fast_api $ pip freeze -> requirements.txt

$ uvicorn main:app --reload
```

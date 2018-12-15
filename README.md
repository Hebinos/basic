# basic
basic codes

## Tips
- source
```
cat ${ipynb_filename} | jq .cells[].source
```

- extensions configuration dir
  - Mac
```
/anaconda3/share/jupyter/nbextensions
```

- Flask
```
pip install Flask
```

- API
```
http://rennnosukesann.hatenablog.com/entry/2018/07/21/155401
```

- launch API server
```
FLASK_APP=hello.py flask run
```

- check
```
curl http://127.0.0.1:5000/hoge?param=helloAPI
```
# Conda を Heroku で動かしてみようとしたやつ
## 説明省略
```
conda update --all
conda install pip
```

## 古いパッケージだけアップデート
```
pip list --outdated | awk 'NR>2 {print $1}' | xargs pip install -U
```

## HerokuがConda非対応だと？
https://stackoverflow.com/questions/52825799/heroku-deploy-error-no-matching-distribution-found-for-anaconda-client-1-6-14

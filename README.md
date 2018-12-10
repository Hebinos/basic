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

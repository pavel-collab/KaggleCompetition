Подготовка данных. Данные для соревнования можно скачать с официальной [страницы соревнования](https://www.kaggle.com/c/playground-series-s3e20/data). Либо с использование kaggle-aip:
```
kaggle competitions download -c playground-series-s3e13
```

__ATTENTION__: перед использованием kaggle-api, убедитесь, что у вас установлен kaggle-api
```
pip install kaggle
```

а также заведен токен на вашей странице kaggle и токен __kaggle.json__ находится в дериктории __~/kaggle/__. Распаковать архив с данными:
```
unzip playground-series-s3e20.zip -p ./data
```
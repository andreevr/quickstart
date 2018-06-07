---
title: "Синхронизация с bucket AWS"
date: 2018-05-23T11:34:59+03:00
---

Для копирования данных из папки используется строчка:  
```
>aws s3 cp --recursive ~/quickstart/test s3://Test_bucket
```          
     
Для синхронизации данных с bucket используется следующая строчка:  
```
>aws s3 sync . s3://Test_bucket/ --acl public-read
```

dfgdfgdfgdf
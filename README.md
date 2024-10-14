# Android Project
JavaでAndroidアプリ開発

## 環境構築
1. Dockerコンテナの起動
```
docker-compose up --build 
```
ターミナルの切り替えを行い下記のコードを実行
```
docker exec -it android_project-java-1 /bin/bash
```

2. バージョン確認
```
java --version
gradle --version
```

3. javaのコンパイル
```
javac HelloWorld.java
java HelloWorld
```

4. dockerコンテナから出る
```
exit
``` 
### Mongo DB 실행


1. Mongo DB Docker download

```
// 아래처럼 특정 version 지정안한 경우 latest download
docker pull mongo
```

2. Mongo DB Docker 실행

```
// 이름 및 포트 지정해서 mongo 컨테이너 이미지 실행
docker run --name docker-mongo -p 27017:27017 mongo
```

3. Mongo DB 내부 접근

```
docker exec -it docker-mongo bash
```

4. Mongo DB 기본 Doc(table) 조회
```
dbs
```
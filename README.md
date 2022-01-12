# mysql-elasticsearch
mysql과 elasticsearch에 대해 동기화하는 작업을 연습하는 저장소입니다.

## 구현 방식
- Logstash의 logstash-input-jdbc 플러그인 사용
    - [가이드](https://www.elastic.co/kr/blog/how-to-keep-elasticsearch-synchronized-with-a-relational-database-using-logstash)
- go-mysql-elasticsearch 라이브러리 사용
    - [가이드](https://github.com/go-mysql-org/go-mysql-elasticsearch)

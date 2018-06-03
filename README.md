# node, ngix, redis 를 이용한 분산 Restful Server Spec

1. Socket.io를 이용한 node 서버 구축 (CRUD - GET, POST, CREATE, DELETE, etc)
2. ngix를 이용한 Proxy 로드밸런싱
    reverse proxy 구축
    serveral upstream server
      - round-robin
      - least_conn
      - ip_hash
      - least_time
    domain이나 regualr expression을 활용한 dynamic proxy는 구성할지 고민
3. redis를 이용한 data cache구현
4. 데이터 베이스 로드밸런싱, 샤딩, 싱크 맞추는 것을 어떻게 구성할지 고민중

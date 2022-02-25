# 가상화
## 가상화
- 운영체제 디버깅을 위해서 1960년대에 가상화 타입1이 만들어짐 
- 하드웨어위에 추상화계층을 올려서 운영 체제를 테스트를 해봄
- 가상화 중 찾은 장점
    - 보안의 우수성
        - 직접 운영체제를 움직이는 것이 아니고 vm을 이용하니 보안이 좋아짐
    - 자원의 효율성
        - 자원을 분배해서 사용하니 효율성이 좋아짐
    - 격리
        - 격리가 되어서 보안이 좋아지고 외부 침입시 직접적 공격이 어려워짐
- 더 연구 끝에 타입 2 개발
- 타입2
    - 하드웨어 운영체제 위에 VM(하이퍼바이져, 게스트OS)을 올려서 가상화 (전가상화)
- 단점
    - 오버헤드
    - 느려짐
## 반 가상화
- 게스트os에게 가상화 상태라는걸 알려줌
반가상화를 이용: 클라우드
## 도커
- 프로세스 격리, 프로세가 혼자 돌고 있다고 착각하게 만듬
- 게스트OS가 없어서 가상화와 다름
- 가상화에 비해 가볍고 성능 좋음
- 대부분의 서비스회사는 도커로 배포
- 규모가 커짐으로 컨테이너가 너무 많아짐
- 관리가 힘들어짐

## 쿠버네티스
- 쿠버네티스의 등장
- 구글이 만든 컨테이너 관리 시스템
- 단점: 어려움
## 데이터베이스 사용 이유
- 검증된 데이터를 신뢰도 있게 읽고 검색할 수 있어서
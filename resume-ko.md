## ✔ Info 

### 이희연 
![image](https://user-images.githubusercontent.com/51354965/172858000-9967e637-cf3f-43f7-9fb7-615a0dbd2799.png)
- Java & Spring 기반 Backend 개발자 (2017 ~ )
- 소프트웨어 공학 학사

### 참고 해주세요

- [LinkedIn](https://www.linkedin.com/in/heeyeon-lee-61763a190/)
- [Blog](https://velog.io/@recordsbeat) <br>
- [GitHub](https://github.com/recordsbeat)

### 연락 주세요
- beathuman@naver.com
- 링크드인 메신저로 연락주세요!


### 경험 해본 것
- **Backend 개발 @NAVER Corp (Sep 2021 - Present)**
  - 마이크로서비스 & 이벤트 드리븐 아키텍처 기반 Backend 개발
  
- **Backend 개발@Wemakeprice(Jul 2020 - Aug 2021 · 1 yr 2 mos)**
  - 마이크로서비스 아키텍처 기반 검색 노출 데이터 개발
  
- **Backend & Web 개발 @Guiving(Aug 2019 - Jun 2020 · 11 mos)**
- **Web 개발@Drift Entertainment(Oct 2018 - Aug 2019 · 11 mos)**
- **Web 개발@DongeunIT(May 2017 - Jul 2018 · 1 yr 3 mos)**
<br>

## 🔨 개발 환경
- Framwork : Spring boot 2.5.x
- SDK : JDK 11, 17 (modern Java)
- IDE : IntelliJ
- Infra : Mysql, Elastic Search, Redis, Kafka
- Monitoring : Grafana, Pinpoint, Spring Admin
- DevOps : Github, Bitbucket, Jenkins, Aws, Kubernetes 


## 🧱 도메인 
### 인플루언서 검색 서비스 (UGC 서비스) @[네이버](https://influencercenter.naver.com) - 재직 중
- 여러 플랫폼(네이버 블로그, 유튜브, 인스타그램, 트위터 등)을 통한 콘텐츠 수집
- 인플루언서 콘텐츠 검색 엔진 노출
- 인플루언서 플랫폼 자체에서도 사용자 생성 컨텐츠 생성 가능


### E-commerce @[위메프](https://wemakeprice.com)
- 상품 카탈로그 분류 및 속성(색상, 크기, 용량) 지정
- 각 카탈로그 최저가 판별
- 카탈로그 최저가 검색엔진 노출


<br><br>



## 💪 이런 것에 자신 있어요

- 의도하지 않은 쿼리 및 성능 저하를 방지하기 위한 JPA(Hibernate) 라이프사이클 파악<br>
[QueryDsl 을 사용한 쿼리 튜닝과 N+1 해결](https://velog.io/@recordsbeat/QueryDsl-%EA%B3%BC-JPA-Repository-%EC%82%AC%EC%9A%A9%EC%B2%98) <br>
[JPA hibernate Query Plan Cache로 인한 OutOfMemory 해결](https://velog.io/@recordsbeat/JPA-hibernate-Plan-Cache%EB%A1%9C-%EC%9D%B8%ED%95%9C-OutOfMemory-%ED%95%B4%EA%B2%B0) 

- 배치 애플리케이션의 트랜잭션 성능 향상 및 lock time 단축 <br>
[JPA를 사용한 트랜잭션 동시성 처리하기]([https://github.com/recordsbeat/resume-eng/blob/a275fd280ca51d9c9df37c48a34e57ebff157ff4/Handling%20Transaction%20Concurrency%20Using%20JPA.md](https://velog.io/@recordsbeat/JPA%EC%97%90%EC%84%9C-Write-Skew-%EB%B0%A9%EC%A7%80%ED%95%98%EA%B8%B0-locking-%EC%A0%84%EB%9E%B5)) <br>

<br>


## 📑 이런 것들을 해요

### 마이크로서비스 테스트 - Component Test  
- Testcontainer, wireMock 사용한 테스트 환경 격리
- 테스트 성능 향상을 위한 Testconatiner reuse 정책 사용
- Method fixture를 사용한 테스트 케이스 묘사 (ex. fixture.given_파라미터가_2개...)
- DBUnit을 사용한 테스트 데이터 초기화 (excel, csv ... )

### CDC(Change Data Capture by Debezium - kafka connect)
- K8s 환경 내 Debezium(Kafka connect) 인스턴스 구축
- DB인스턴스 failover 전략 수립
- Kafka connect 운영 관리 툴 Poc (UI for Apache Kafka 선정)
- 부하 테스트를 통한 데이터 동기화 지연 정도 측정
- [이벤트 드리븐 환경 내 CDC 도입 경험](https://velog.io/@recordsbeat/%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EB%93%9C%EB%A6%AC%EB%B8%90-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98%EC%97%90-CDC-%EC%A0%81%EC%9A%A9-%EC%88%98%EA%B8%B0)

<br><br>


## 👂 What I’m interested in

### Virtual thread (a.k.a project loom) 
- Lightweight thread(fiber) will set us free from thread performance so that we don’t need to deal with non-blocking operation for performance

### Shenandoah GC (a.k.a Low-pause)
- Load reference barrier enables not only concurrent marking swap but also compact(evacuation) 
- Expect it will shrink GC pause time dramatically at Server API application

[Low-Pause ! Shenandoah GC - from my blog](https://github.com/recordsbeat/resume-eng/blob/a275fd280ca51d9c9df37c48a34e57ebff157ff4/Low-Pause%20!%20Shenandoah%20GC.md) <br>

### Consumer Driven Contract Test (a.k.a Pact)
- Consumer generates Pact, so client side won't need to wait anymore until server gives Api spec(such as swagger)
- Pact broker shows commnication relcationship between each microservice
- Handling Pact's version and history easliy (living document)
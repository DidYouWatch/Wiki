# 개요

## 프로젝트 명 : Did you watch?


Did you watch는 영화, 드라마, 스포츠 등 다양한 컨텐츠에 대한 반응을 공유하고, 그 반응으로부터 통계를 산출해 사용자들에게 새로운 경험을 줄 수 있는 플랫폼입니다. 간단한 댓글로부터 시작하여 투표, 채팅 등 더 다양한 반응을 수집할 수 있도록 나아가고자 합니다.

# 특징

- 이 프로젝트의 아이디어는 이전에 진행했던 프로젝트인 Contents-issue-project([https://github.com/Contents-Issue-Project](https://github.com/Contents-Issue-Project))에서 출발했습니다. 해당 프로젝트는 express 사용자서버 + python 배치서버 + android 애플리케이션으로 구성되어 있었습니다.
- 이 프로젝트에서는 더 꼼꼼한 사용자스토리 추출과 마이크로서비스를 기반으로 유연성 높은 설계를 지향합니다.
- 프론트 엔드 개발보다 백엔드 개발을 우선시하지만, 백엔드 개발 내용이 사용자의 실제 요구사항과 동떨어지지 않도록 '스토리보드'는 작성한 후 백엔드 개발을 진행합니다.

# 주요 기술 스택

> 스택의 활용 방침과 예시에 대한 자세한 내용은 wiki에 추가될 예정입니다.

- Microservice
    - Event Storming
    - Domain Driven Design
    - 12factor
- Spring Boot
    - Spring Security
    - Spring Boot Actuator
    - Spring Boot Admin
    - Spring Data JPA
    - Spring Data Mongo
- Spring Cloud
    - Service Discovery
    - API Gateway
    - Kafka
    - Feign
- Persistence
    - JPA
    - Querydsl
    - Mongodb
    - Redis
    - Elasticsearch
- Cloud service
    - GKE for deployment
    - GCP Cloud Functions for Data Processing
    - GCP workflows for Implementing statistical generation process

# 개발 진행 상황

이 프로젝트가 최종적으로 다루고자 하는 기능들은 매우 넓기 때문에, 전체 사용자 스토리를 분할해 이터레이션을 구성하여 차근차근 개발해나갈 계획입니다.

- 사용자 스토리 보완(https://github.com/DidYouWatch/Wiki/wiki/UserStory)
- 이벤트 스토밍(https://github.com/DidYouWatch/Wiki/wiki/EventStorming)
- 마이크로서비스 정의(https://github.com/DidYouWatch/Wiki/wiki/Snap)
- 사용자 스토리 우선순위 결정
- 이터레이션 분할(https://github.com/DidYouWatch/Wiki/wiki/iteration)
- 마이크로서비스 인프라 구축(https://github.com/DidYouWatch/Wiki/wiki/architecture)
- 이터레이션 반복(iteration2 진행중 https://github.com/orgs/DidYouWatch/projects/3)

마이크로서비스 인프라 구축부터는 github issue에 진행상황이 추가될 예정이니 참고 바랍니다.

# 문서

https://github.com/DidYouWatch/Wiki/wiki

구현중 다루는 기술들에 대한 내용은 프로젝트 wiki와 블로그([https://tech.junhabaek.net/](https://tech.junhabaek.net/))에 업로드될 예정입니다.

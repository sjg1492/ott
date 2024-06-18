## 소개
본 프로젝트는 JPA,NoSql,대용량 데이터 처리를 연습하기 위한 목적으로 작성하였으며 <br/>
OTT 다양한 정보 제공 플랫폼을 제공합니다.
&nbsp;

&nbsp;


## 패키징 구조
도메인형 디렉터리 구조를 사용하여 각 도메인별로 관련 클래스들을 모아두어 <br/>
코드의 가독성과 유지보수성을 높였습니다.
&nbsp;

&nbsp;




## 객체지향 프로그래밍 (OOP) 적용
본 프로젝트는 OOP 원칙을 준수하여 상속과 인터페이스를 활용해 확장성을 높였습니다.

 - **도메인 계층 설계**: 엔티티, 리포지토리, 서비스, 컨트롤러로 구성되어 있습니다.<br/> 이를 통해 도메인별로 기능을 모듈화하고, 변경에 유연하게 대응할 수 있도록 했습니다.
 - **효율적인 코드 작성**: 프로젝트 규모에 맞는 적절한 상속을 통해 코드의 확장성 및 가독성을 높였습니다.
&nbsp;

&nbsp;


## 기능 목록
 - **회원가입**: 사용자는 회원가입을 통해 서비스에 가입할 수 있습니다.
 - **로그인**: 사용자는 SNS 로그인하여 JWT 인증 토큰을 발급받을 수 있습니다.
 - **내 정보 보기**: 로그인한 사용자는 자신의 정보를 확인할 수 있습니다.
 - **컨텐츠 조회**: 외부 API에서 컨텐츠 관련 정보를 조회하여 확인할 수 있습니다.
 - **컨텐츠 상세 조회**: 컨텐츠에 해당하는 상세 내용을 확인할 수 있습니다.
&nbsp;

&nbsp;


## 추가 기능 
 - **AOP 적용**: AOP(Aspect-Oriented Programming)를 통해 사용자의 요청 파라미터와 응답값을 로깅하여<br/> 디버깅과 모니터링을 용이하게 하였습니다.
 - **멀티스레드 데이터 처리**:멀티스레드를 활용하여 처리함으로써 API 응답 시간을 최적화했습니다.<br/> 이를 통해 서버 자원의 효율성을 높였습니다.
&nbsp;

&nbsp;


## 기술 스택
- Java 17
- Spring Boot 3.3
- JPA
- WebClient
- H2 Database (Memory Mode)
- Gradle


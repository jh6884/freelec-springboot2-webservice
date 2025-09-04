## 테스트 코드를 쓰는 이유
1. 초기에 문제를 발견할 수 있음.
2. 업그레이드 등에서 기존 기능이 올바르게 작동하는지 확인 가능함.
3. 불확실성을 감소시킬 수 있다.
4. 문서화가 가능하다.

## 테스트 코드
1. 빠른 피드백
2. 자동 검증
3. 개발자가 만든 기능을 안전하게 보호

## 테스트 코드 프레임워크
- JUnit5 - java

## 프로젝트 구조
- build.gradle
  - 역할: 프로젝트 빌드 설정, 의존성 관리, 롬복 포함 등
- HelloController.java
  - 역할: HTTP 요청 처리, API 엔드포인트 제공
  - 동작의 흐름:
    - 브라우저 요청 GET/hello
    - HelloController.hello() 실행
    - hello 문자열 반환
    - 브라우저에 hello 표기
- HelloResponseDto.java
  - 역할: API 응답시 데이터를 담는 객체
# k-wasm-app

K-WASM 앱 구현을 위한 레파지토리입니다.

<개발환경>
 - 언어 : 자바 17(OpenJDK 가능)
 - 공통 주요 프레임워크 : Spring Boot Frameworks 3.16
 - 개발도구 : IntelliJ
 - 빌드도구 : Gradle 8.5
 - 인프라 환경 : K-PaaS 인프라 적용
  
<구현 앱>
1. app-manager
 - MSA 아키텍처 적용에 따른 다양한 앱을 관리하는 UI 앱 서비스
 - 적용 프레임워크 : Spring Boot Admin
 - 도커 이미지 생성 파일 : Dockerfile
 - 도커 이미지 파일 다운로드 링크 : 
     
2. config-file
 - 앱에 적용된 환경 설정 분리를 위해 환경설정 파일들이 저장되는 저장소
 - 적용 프레임워크 : 없음
      
3. config-server
 - 환경 설정을 위해 Spring Cloud Config Server를 적용한 Config Server
 - 적용 프레임워크 : Spring Cloud Config Server
 - 도커 이미지 생성 파일 : Dockerfile
 - 도커 이미지 파일 다운로드 링크 : 

4. eureka-server
 -  서비스 디스커버리 등 서비스 관리를 위해 구현
 - 적용 프레임워크 : Spring Cloud Netflix Eureka Server, Spring Boot Actuator
 - 도커 이미지 생성 파일 : Dockerfile
 - 도커 이미지 파일 다운로드 링크 :
   
5. ui-html
 - HTML 기반 K-WASM앱 UI
 - 도커 이미지 생성 파일 : Dockerfile
 - 도커 이미지 파일 다운로드 링크 :

6. test-data
 - WASM 컴파일 테스트하기 위한 프로그래밍언어 파일 

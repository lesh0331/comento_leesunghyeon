#코멘토_직무부트캠프_IT 대기업 현업 개발자와 함께 하는 백엔드 개발 실무

## 주간보고내용 - 1주차

1. 개발환경 셋팅
    - JDK 1.8 설치 및 환경변수 설정
    - Eclipse, Spring 다운로드 및 설치 (이클립스 기반으로 된 STS를 Spring 프레임워크를 공식 사이트에서 설치)
    - 톰캣 설정
      
2. 1주차 활동 내용
    - Hello World 출력 (Spring Lagacy Project 생성 -> pom.xml에서 스프링 버전/JDK버전을 수정 -> 서버 세팅 후 출력)
    - mariaDB, mySql WorkBench 설치 및 샘플 DB 구축
      
              insert into movie(movie_id, movie_name, director, types)
                values(1,'아이언맨','감독1','SF'),
                (2, '스파이더맨','감독2','SF'),
                (3, '라이온킹','감독3','다큐멘터리');
      ![table](https://github.com/lesh0331/comento_leesunghyeon/assets/69080831/c2d303e9-6999-4e19-8c38-d3fbceda1eb2)

      
    - 스프링, Mariadb, MyBatis 연동, 데이터 조회    
  
## 주간보고내용 - 2주차(API 가이드 문서 작성)

1. 요청사항
   - (1) 인터페이스 가이드 문서 작성

   - (2) SW활용률(접속자 수, 부서별 접속자 수, 로그인 요청 수, 게시 글 작성 수)  
         에 필요한 데이터를 해당 내용에 맞게 문서를 작성  
         (요청 파라미터 생각, 응답 데이터 포맷 고려)

2. 2주차 활동 내용
   - (1) 접속자 수에 필요한 데이터 (요청 파라미터, 응답 데이터 포맷) 고려하기
   - 
     (2) 요청 파라미터 :
       
         ㄱ. 접속자 수 조회 : total_user(총 조회된 접속자 수), user_id(ID의 유저 접속현황 조회), period(조회 기간)   
         ㄴ. 부서 별 접속자 수 조회 : department_id(조회된 부서의 ID), department_name(조회된 부서의 이름), total_user(총 조회된 접속자 수), period(조회 기간)   
         ㄷ. 로그인 요청 수 조회 : login_request(총 로그인 요청 수), user_id(ID의 유저 로그인 요청 수 조회), period(조회 기간)   
         ㄹ. 게시글 작성 수 조회 : total_post(총 작성된 게시글 수), user_id(ID의 유저 게시글 작성 수 조회), period(조회 기간)  

   - (3) 응답 데이터 포맷 : JSON
  
3. 궁금한 점
   - 처음 작성해보는 API 가이드 문서여서 최대한 샘플을 활용하고 검색을 통해 공부해가며 작성해보았지만  
     제가 잘 이해했는지, 알맞게 작성했는지 잘 모르겠습니다..  
     특히 "요청 파라미터"가 무엇인지 이해하는 것 과 어떤 파라미터가 있어야 적절할지, 고민하는 시간이 길었던 것 같습니다.  
       
     또한 2주차의 내용은 어떤식으로 README.md(주간보고내용)에 작성해야 할 지 잘 모르겠어서  
     작성된 가이드 문서의 내용을 넣었지만, 주간보고내용에 알맞지 않은 것 같아 아쉬움이 남습니다..  
     어떤 내용이 들어갔어야 모범 답안일지 궁금합니다.  
       
     혹시 제가 잘못 이해하고 있는 부분이나, 잘못 작성된 부분이 있다면  
     피드백 해주시면 감사하겠습니다!  
  
    "(수정)API 가이드 문서"를 열람해주시면 됩니다!

## 주간보고내용 - 4주차

- 공공데이터 사이트 공휴일 오픈API 활용
- Holiday.java(공휴일 정보를 나타내는 엔터티)
- HolidayRepository.java(데이터베이스 읽고 쓰기)
- OpenApiController.java(공공데이터의 공휴일 정보를 조회)
- OpenApiExplorer.java(공공데이터 사이의 API를 호출)
- OpenApiService.java(공휴일 정보를 처리하고 데이터베이스에 저장)
- 조회를 위한 test.jsp 코드 추가
- 공휴일 데이터베이스 추가
- ![스크린샷 2023-12-17 204810](https://github.com/lesh0331/comento_leesunghyeon/assets/69080831/e86b5797-4ee8-437f-811e-51d27cf6a677)



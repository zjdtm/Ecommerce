# Ecommerce 프로젝트 Self-Code 강의 참조(https://www.youtube.com/@self-code/featured)

강의를 보면서 공부했던 내용을 정리하기 위한 리드미이다.

# 1. Multi-Module 프로젝트 설정
  먼저 Multi-Module이란 서로 다른 즉, 독립된 프로젝트를 하나로 묶은 것을 뜻하며 이렇게 서로 독립된 프로젝트는 기능별로 명확하게 분리되어 있을 뿐더러,공통된 코드를 여러 곳에서 참조가    가능하기 때문에 기능 수정시 모든 프로젝트를 수정할 필요가 없다는 장점 등을 가지고 있다.
  ![image](https://user-images.githubusercontent.com/35757620/209612386-ef328d8b-6fe9-40d5-aedd-6c7ba50305cb.png)
  ![image](https://user-images.githubusercontent.com/35757620/209612472-386ef1da-53e4-426b-be83-01f475c45d74.png)
  
# 2. Spring-Security 설정
  Error
  ![image](https://user-images.githubusercontent.com/35757620/209665388-c2ab3010-e10b-4e5c-bdbf-8f21f4a34e04.png)
  스프링 시큐리티를 설정 한 후 정적 파일들을 가져오지 못하는 상황이 발생하였다. 구글링을 통해 확인해 보니 css 파일이나 js 파일 등에도 필터가
  적용된다는 사실을 알아냈고 메서드 설정을 추가하면 해결할 수 있다는 것을 발견했다.
  ![image](https://user-images.githubusercontent.com/35757620/209665617-50e08748-bc45-4eb3-97ef-e07089752e9e.png)
  이렇게 설정한 후 재실행을 해보았다 css랑 이미지 파일은 가져온 것을 확인 할 수 있었지만 아직도 에러 로그는 남아있는 상태이다
  조금더 검색을 해본 후 해결해 보도록 하겠다.


  





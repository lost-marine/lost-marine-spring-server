# :ocean: Lost Marine 로스트마린
> 환경 보호와 생물 다양성을 주제로 전개되는 바다 속 서바이벌 게임

- 멸종위기 해양생물 캐릭터를 조작하여 바다 속을 탐험
- 플랑크톤과 미세 플라스틱을 먹으면서 레벨업 및 체력 관리
- 다른 플레이어와의 전투를 통해 경쟁과 전략적 요소 추가
- 쉬는 동안 게임 내 지식 콘텐츠를 통해 실제 환경 문제에 대한 정보 전달

## 개발 환경
- Spring Boot 3.2.4
- Java 17 

## 폴더구조

```
src
  ㄴmain
    ㄴ java
         ㄴ global
              ㄴ config
                   ㄴ Config.java
              ㄴ common
                  ㄴ code
                  ㄴ request
                  ㄴ response
             ㄴ exception
         ㄴ domain
               ㄴ player
                  ㄴ entity
                  ㄴ repository
                  ㄴ controller
                  ㄴ exception
                  ㄴ service
                  ㄴ dto
                      ㄴ request
                      ㄴ response
   ㄴresource
      ㄴ application.yml	
```

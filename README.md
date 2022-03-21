# KSPYFALL

블로그 완성된지 얼마나 되었다고 또 토이플젝을 하나 시작해버렸습니다

목표는 이번달 말까지 빠르게 기능적인 것은 구현하는 것입니다.

[기획하는 db 형태](https://www.erdcloud.com/d/TjmK222oBQPzqWMKZ)

----

처음에는 자연스럽게 django랑 channels를 이용해서 백엔드를 짤려고 했는데 생각 이외로 좀 형태가 많이 달라서 지금 django를 내려둘까 고민중

코틀린 스프링으로 조금 고민중

---

백엔드 코틀린으로 변경 일단 현재 시큐리티까지 넣고 작업 완료. 컨밴션은 아래 규칙을 따른다

## conventional commits

- feat: 기능추가 
- fix: 버그수정 
- docs: 문서수정 
- style: 코드포맷팅 등 논리수정없는 코드 변경 
- refactor: 리팩토링 
- test: 테스트코드 
- chore: 패키지 설치
- 여기에 frontend작업인지 backend작업인지만 추가적으로 설명을 붙인다
  - `feat-frontend` , `style-backend`
  - 간단한 문서같은 경우에는 스킵 가능

## code convention

- 클래스: UpperCamelCase
- 함수: lowerCamelCase (동사로 시작할 것)
- 변수
  - 고정 상수값: UPPER_CASE
  - 이용할 변수: lowerCamelCase (명사 형태로)

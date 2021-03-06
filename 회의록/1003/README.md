# 2019/10/03 회의 및 스터디

## 역할 구성

- 프론트
  - `정구헌`
  - `김주희`
- 백엔드
  - `김준목`
  - `이승순`

## 프론트 회의

- 작업 내용
  - 발화 시나리오 작성(USE CASE)
  - 시나리오에 맞춰 각 페이지 제공 기능 정의
  - 페이지 view 초안 작성
  - 커스텀 범주(category) 목록 작성
  - 도수 기준, 용량 기준, 제조 도구 대체품 목록 작성

- 회의 내용
  - 성인 인증 문제 - permission(개인정보동의 제공) <- 핸드폰 또는 구글 인증 등이 필요할 수 있다
  - 분기 조건 문제
  - 조리 하는 이미지 -> 칵테일 제조 기법 이미지로 대체
  - 조리 순서 사진이 거의 없기 때문
  - 필수 재료와 서브재료를 나눠서 저장
  - [뷰초안](#프로토-타입-구성)

- 추후 일정
  - 강의 학습
  - 유사 예제 분석
  - 뷰 만들기
    - 데이터에 상관 없이 화면에 뿌리기
    - 화면 간 이동
    - 스크립트
  - 각자 나눠서 뷰 제작
  - 백엔드 연동

## 프로토 타입 구성

- ![ㅁ](/회의록/1003/칵테일_설명.JPG)
- ![ㅁ](/회의록/1003/베이스_조회.JPG)
- ![ㅁ](/회의록/1003/범주리스트_조회.JPG)
- ![ㅁ](/회의록/1003/리스트_조회.JPG)
- ![ㅁ](/회의록/1003/레시피_페이지.JPG)

## 백엔드 회의

- 작업 내용
  - firebase 연동 시도
  - js 기본 문법 공부

- 회의 내용
  - firebase 연동에 어려움을 겪음
    - google email support에 문의 (예상 답변일 1007)
  - 불가능하다고 판단이 되면 최대한 빠른시간내에 새로운 DB선택
  - 대체재를 위한 다양한 예제 수집

- 추후 일정
  - JS에서 firebase를 직접 사용 가능한지 확인
    - firebase에서 functions를 활용하여 연동 가능한 것으로 확인(구현 관련 스터디 필요)
  - 사용이 불가능 하면 사용할 DB 재선택
  - DB 데이터 확인되면 DB 구축 시작
  - 프론트와 상의 후 뿌릴 데이터 정리
  - 테이블 생성 및 데이터 수집, 입력

## 사용 툴

- 캡슐 개발 전용 스튜디오
- 깃헙
- 슬랙, 트렐로

## 향후 일정

(별첨) 바텐더 캡슐 일정 참고
![일정표](/회의록/1003/바텐더_2차_일정표.JPG)

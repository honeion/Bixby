# 191006 Front 팀 작업 내용

## 프로토 타입 구현
#### 칵테일 조회 뷰
![01_칵테일 조회 뷰](/1006_view_prototype완성/image/01_칵테일_조회_뷰.PNG)

#### 재료 조회 뷰
![02_베이스 재료 술 조회 뷰](/1006_view_prototype완성/image/02_베이스_재료_술_조회_뷰.PNG)

#### 칵테일 리스트 뷰
![03_칵테일 리스트 뷰](/1006_view_prototype완성/image/03_칵테일_리스트_뷰.PNG)

#### 레시피 조회 뷰
![04_레시피 조회 뷰](/1006_view_prototype완성/image/04_레시피_조회_뷰.PNG)


## DB 논의
### 기존 : cocktail, material 테이블 조인해서 사용
### 개선 : cocktail 테이블 하나만 사용
필수재료, 서브재료, 추천칵테일 (재료일 경우 그 재료가 들어가는 칵테일) 컬럼 추가

컬럼내용

> 공통 : 이름, 분류, 도수, 설명

> 칵테일에만 : 필수재료, 서브재료

> 재료에만 : 추천칵테일, (대체재)


## Front 팀 TODO
<ol>
  <li>발화 - 단어는 다르지만 뜻은 동일한 단어(이음동의어)들에 학습 필요</li>
  <li>요소 클릭시 화면으로 이동하게 링크 설정</li>
  <li>범주화 & 기준 재 설정</li>
  <li>칵테일 제조 방법 및 재료의 양을 쉽게 파악할 수 있도록 정보 제공</li>
  <li>저작권에 위배되지 않도록 칵테일 사진 구하기</li>
</ol>

## 참고
무료 아이콘 링크 : https://www.flaticon.com/

(왕관 아이콘이 없는 이미지에 한하여 상업적 사용 가능)

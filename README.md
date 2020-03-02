# Simple_Web_Practice
making simple web at least once a week
## 프로젝트 동기
- 공부한 내용들을 정리하고 실습하기 위한 repository입니다.
- 사용언어: html, css
- 사용에디터: vscode
- 참고: 구름EDU 미운우리 웹 백조

## 블록과 인라인 세상 들여다 보기

- block elements와 inline elemets에 대한 설명
- 상속의 개념, 우선순위(구체적일수록 높음 예: 클래스 선택자>태그 선택자)
- display: inline-block -> border가 글자 수에 맞춰진다.
- display: block-> a태그에 사용하며 a태그는 inline속성이라 본래는 margin은 좌우만 적용되고, padding도 제대로 적용되지 않는다. 블록화를 하여 이를 해결한다. 
- 가로정렬:인라인, 세로정렬:블록
- 이미지 태그는 inline속성이다.

## CSS 타이포그래피

- line-height의 개념
- line-height의 기본값은 normal
- 1이되면 16px로 고정됨-> 폰트크기 바뀌어도 절대적인 크기가 변하지 않음.

## float 속성으로 가로배치하기

- inline-block의 한계 극복
- 부모에 종속을 벗어난 떠있다는 개념

## float속성으로 가로배치하기 두번째 이야기

- display: flow-root의 개념, 최신개념
- overflow: hidden, 낯선개념 학습.

## Position속성 입문하기

- position relative 주위에 영향을 끼치지 않고(자신의 현재위치가 기준이됨), 위치를 바꾼다.
- position absolute와 구별
- 가까운 부모가 기준점, position relative 하면 그 안에 있게 됨.
- 미니예제, %와 negative-margin
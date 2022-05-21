# Coin Tracker

<br/>

## 소개
React로 Coinpaprika API를 호출하고, 가상 화폐의 랭킹과 각 가상 화폐의 현 시세, 지난 시세 등을 그래프와 표로 확인 할 수 있는 웹 사이트를 구현하였습니다.

<br/>

## 구현 기능
  - React Query를 사용해 Coinpaprika API를 호출
  - light mode / dark mode 구현
  - 정보들이 모두 로드 될 때까지 loading 텍스트를 띄우도록 구현
  - 코인 종목을 클릭하면, 클릭한 코인의 id를 받아와 coin 페이지에서 얻은 정보를 화면에 구현
  - Nested Routing으로 해당 코인의 Chart와 Price 카테고리를 만들어 클릭을 하게 되면 해당 정보를 보여주도록 구현
  - Apexcharts 라이브러리를 사용해 깔끔한 차트를 구현

<br/>

## 사용 기능
### React
### React Typescript
### styled-components
### React Router Dom
### React Query
  - fetch보다 간단하게 api를 호출하기 위해 사용하였습니다.
### Recoil
  - theme파일에 저장해둔 배경과 폰트 색상을 이용하기 위하여, dark mode를 구현하였습니다.
### Apexcharts
  - 코인의 시세 정보를 가져와 인터렉티브하고, 깔끔한 차트로 시각화 하였습니다.

<br/>

## 스터디 노트
[Coin Tracker 강의 정리](https://velog.io/@bomida/React-Coin-Tracker-강의-정리)

<br/>

## 개발 환경
  - 개발도구: VSCode, Github
  - 사용언어: React JS, react-typescript

<br/>

## 레퍼런스
  - [Nomadcoder](https://nomadcoders.co/?gclid=Cj0KCQjwm6KUBhC3ARIsACIwxBhCS_ap9R7ZfV9msXf-rAMieBlbzGjk0kC4U_XkIYjY-BATk_zhSZ0aAm9-EALw_wcB)
# About Content 부분 layout 잡기

1. 하나의 컴포넌트를 이용해서 img 부분 content 부분을 분기해서 사용할까? 아니면
   따로따로 만드는게 재사용하기 좋을까?

- 따로따로 만들어서 하는게 좋을 것 같다. img 부분은 src , content 부분은
  children 또는 props로 해결해보자

- 각 type마다 불러오는 대표이미지들을 다르게 하면 좋을 것 같다. -> 결국엔 데이터
  저장시 type도 고려해서 저장해야 하며, 대표이미지는 어떠한 필드를 추가해서 불러
  올지 결정해야 한다.

- 우선 데이터 있다는 가정하에 dummy로 집어넣어서 레이아웃 확인해보기

- 레이아웃 잡아놓음

## Box Model
1. content 
- 텍스트및 이미지 영역
2. padding
- content와 border사이의 여백
3. border
- padding 주위를 둘러싸는 테두리
4. margin
-border외부영역

##
1. *{
box-sizing: border-box 
  }
- border를 기준으로 px계산

2.block

따로 width 를 선언하경우 , 남은공간은 margin으로 자동으로 채움
영역을 잡기위해 사용

3.inline


block과 반대 성질 ,인라인은 흐름과 같음
height, padding top/bottom , magin top/bottom 사용불가 


4.Float

어떤 요소를Float 시키면 Inline Block -> block이됨

5.Positon
요소를 원하는 위치에 자유롭게 옮기기위해 사용
- static
모든 요소의 기본 포지션값
- relative
이동 기준: 자기자신이 있던자리

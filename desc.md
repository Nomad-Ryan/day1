* display 의 종류에 따라 tag가 분리된다.
   * block:  div, h1~h6, ul, li, p, section, header, footer....
   * inline:  span, a, img, input, em,
   
* dummy text -> lorem10 단어수를 입
터
* 셀렉터의 개념
    * tag 셀렉터
    * tag의 자식요소를 선택할경우에는 띄어쓰기를 한다.
    
* 센터정렬
    * 블럭요소일 경우
        * 부모보다 작은 width 준다.
        * 부모의 넓이와 차이만큼 발생한 자동마진을 반으로 쪼개서 반대편으로 배치한다.
    * 인라인요소일 경우
        * 부모에게 text-align:center 스타일을 준다.
            * 왼쪽은 text-align:left, 오른쪽은 text-align:right
    
    
* 텍스트는 
    * 인라인요소다.
    * 텍스트 관련 속성이 상속됩니다.

* display
    * block요소의 특징:
        * 부모에게 넓이가 꽉찬다. 그말인 즉슨 width 100%
        * 센터정렬은 부모보다 작은 width를 주고 margin을 auto로 줘서 양쪽으로 반으로 나눈다.
        * width, height 같은 size 속성을 갖는다.
    * inline 요소의 특징
        * 자기자신의 크기만 갖는다.
        * 센터정렬은 부모에게 text-align: center 를 준다
        * width, height 같은 size 속성이 없다.
        
    * inline-block 요소의 특징
        * size 속성을 갖는 inline 요소라고 생각하면된다. 


* reset.css
    * 브라우저의 기본속성을 리셋시켜준다.
    * 디자인과 동일하고 예측가능한 사이트를 구성하기 위해서


* display:flex
    * 

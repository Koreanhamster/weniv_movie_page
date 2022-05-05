Sass를 사용한 영화목록 페이지 클론코딩
====
https://koreanhamster.github.io/weniv_movie_page/
미리보기
![image](https://user-images.githubusercontent.com/95600994/166624369-523809f7-07fe-4ce2-ba00-8ab30fba4ba5.png)


## 기술스택
- HTML, Sass(Scss)

## 적용기술
- 그리드 적용      
![image](https://user-images.githubusercontent.com/95600994/166628512-549e660a-d1d0-4949-bb56-73d14845d027.png)
- 아이템 모듈화하여 중복적용    
![image](https://user-images.githubusercontent.com/95600994/166628599-bd178777-b6e3-4fc1-a67a-d8e87d6705a9.png)
- footer 포지셔닝은 body에 min-height를 100vh를 준 뒤 footer박스에 margin-top을 0으로 주어 처리     
![image](https://user-images.githubusercontent.com/95600994/166628770-918fbc49-e73a-4b40-a350-aa1544545cdb.png)

## 아쉬운점, 배운점
- 예매하기와 예고편 버튼을 스타일링하고 포지션하는데 어려움이 있었는데, 일단 반응형이 전혀 고려되지 않고 네거티브 마진을 주는 식으로 버튼이 부모요소에 꽉 차있는것 '처럼' 스타일링을 했기 때문이다.
- 박스 스타일링은 overflow:hidden을 주어 부모의 border-radius에 맞춰주었다.
- 아직 inline요소들의 vertical align을 맞추는건 여전히 고통스럽다.

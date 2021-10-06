## Do it 클론코딩 영화 평점 서비스

영화 평점 서비스 라는데 인터엑티브한 작용 없이 데이터를 들고와 화면에 구성하는 작업만 한다.

하지만 리액트를 처음한다면 기초적으로 해볼만한 책이다. 책값도 싸다

#### 데이터흐름

yts 에서 영화목록을 조회할 수 있는 api 를 제공한다. 

문제는 주기적으로 키값이 바뀌기 때문에 고정적으로 들고 올 수 있는 proxy 서버를 니꼴샘이 만듬

 https://yts-proxy.now.sh/list_movies.json?sort_by=rating

에서 json 데이터를 들고온다.

이제 이걸로 화면구성을 하면 끝!

![화면 캡처 2021-10-06 112619](https://user-images.githubusercontent.com/51068026/136131247-da6f0f51-3a64-4317-a03d-0d2d96731aae.png)

기초적인 리액트의 JSX, 컴포넌트, CSS를 경험해볼 수 있다.

이걸 NEXT JS로 리팩터링 하는 프로젝트도 진행해보는 중

#### 깃허브 사이트와의 연동

 이걸 깃허브에서 서비스하게 바꾸어 볼 수 있는게 흥미진진했다.
 
 업로드 사이트 : https://JungSangHyup.github.io/Do_It_movie_app
 
 여기에서 직접 사이트를 볼 수 있다.
 
 



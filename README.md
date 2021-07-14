# clone-starbucks
### Favicon(파비콘, favorites icon)
웹페이지를 나타내는 아이콘, 웹페이지의 로고를 설정<br>
대부분의 경우 루트 경로에 favicon.ico 파일을 자동으로 로딩하여 따로 <link>를 할 필요가 없다.<br>
다른 이미지를 아이콘으로 사용하고 싶은 경우 루트 경로에 이미지를 두고 <link>를 해야한다.
```
<link rel="icon" href="./favicon.png" />
```


### 오픈 그래프(The Open Graph protocol)
웹페이지가 소셜 미디어로 공유될 때 우선적으로 활용되는 정보
* og:type: 페이지의 유형(E.g, website, video.movie)
* og:site_name: 속한 사이트의 이름
* og:title: 페이지의 이름(제목)
* og:description: 페이지의 간단한 설명
* og:image: 페이지의 대표 이미지 주소(URL)
* og:url: 페이지 주소(URL)

### 트위터 카드(Twitter Cards)
웹페이지가 소셜 미디어(트위터)로 공유될 때 우선적으로 활용되는 정보를 지정
* twitter:card: 페이지(카드)의 유형(E.g. summary, player)
* twitter:site: 속한 사이트의 이름
* twitter:title: 페이지의 이름(제목)
* twitter:description: 페이지의 간단한 설명
* twitter:image: 페이지의 대표 이미지 주소(URL)
* twitter:url: 페이지 주소(URL)

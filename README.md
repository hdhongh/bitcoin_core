# bitcoin_core
bitcoin core 분석 Daily Log(2018/05/08)
- https://github.com/bitcoin/bitcoin.git 에서 Local Repo로 git clone 수행
- bitcoin core 분석 위해 http://daddynkidsmakers.blogspot.kr/2018/02/blog-post_22.html 참조
- bitcoin 주소 1HB5XMLmzFVj8ALj6mfBsbifRoD4miY36v 와 같이 숫자+문자로 표현됨.
  -> 본래 1과 0으로 표현된 160자리의 이진수이지만 표현하기 어려워 이진수를 58개의 숫자와 문자로 변환해서 표현( 헷갈리기 쉬운 O I 등 제외 )

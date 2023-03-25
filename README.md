# HTML-CSS-tutorial

# 웹폰트 넣는 법
CSS파일에서 
@font-face {
  font-family: '작명~~~';
  src: url(./font/diablo\ light.TTF);
}
body {
  font-family: '작명~~~';
}
한글폰트는 사이즈가 너무 크다~ 1~2개만 쓰자.
용량을 줄이려면 .ttf 말고 .woff 쓰자.

# px, vw(화면기준), vh(화면기준), %(부모기준), rem(html 폰트사이즈의 x배-기본은 16px), em(내 폰트사이즈의 x배)

# breakpoint
1200px 992px 768px 576px

# img태그
img태그는 하단에 약간의 여백이 있는데 display:block 을 주면 없어진다.
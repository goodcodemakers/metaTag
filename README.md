# metaTag
-metaTag에 대하여 정리 or mataTag 사용정의
```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
기본적인 메타태그로 쓰이는 메타태그이며
<b> 인코딩 설정과 뷰포트 설정</b>담당합니다.

아래의 meta 태그는 <b>검색 엔진 최적화 (SEO)</b>를 위한 태그이다.
```html
<meta name="description" content="페이지에 대한 간단한 설명">
<meta name="keywords" content="페이지와 관련된 키워드들">
<meta name="author" content="페이지의 작성자">
```
아래의 태그는 Open Graph 프로토콜을 활용한 소셜 미디어 공유를 위한 태그이다.
  공유를 하였을 때 미리보기를 나타내는 태그
  ```html
<meta property="og:title" content="공유할 페이지 제목">
<meta property="og:description" content="공유할 페이지 설명">
<meta property="og:image" content="공유할 이미지 URL">
<meta property="og:url" content="공유할 페이지 URL">
```

웹 앱 설치 및 홈 화면에 추가를 위한 태그
```html
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<link rel="apple-touch-icon" href="아이콘 이미지 URL">
<link rel="manifest" href="manifest.json">
```

보안 및 권한 설정을 위한 태그
```html
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
<meta name="referrer" content="no-referrer">
<meta name="robots" content="noindex, nofollow">
```
"robots": 검색 엔진이 페이지를 어떻게 색인할지 지정합니다.
"revisit-after": 검색 엔진이 페이지를 재색인할 주기를 지정합니다.
"googlebot": Google 검색 엔진이 페이지를 어떻게 색인할지 지정합니다.
"language": 문서의 언어를 지정합니다.
```
<meta name="revisit-after" content="7 days">
<meta name="googlebot" content="index,follow">
<meta http-equiv="content-language" content="en">
```

# metaTag
-metaTag에 대하여 정리 or mataTag 사용정의

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
기본적인 메타태그로 쓰이는 메타태그이며
<b 인코딩 설정과 뷰포트 설정<b>담당합니다.

아래의 meta 태그는 <b>검색 엔진 최적화 (SEO)<b>를 위한 태그이다.
<meta name="description" content="페이지에 대한 간단한 설명">
<meta name="keywords" content="페이지와 관련된 키워드들">
<meta name="author" content="페이지의 작성자">

아래의 태그는 Open Graph 프로토콜을 활용한 소셜 미디어 공유를 위한 태그이다.
<meta property="og:title" content="공유할 페이지 제목">
<meta property="og:description" content="공유할 페이지 설명">
<meta property="og:image" content="공유할 이미지 URL">
<meta property="og:url" content="공유할 페이지 URL">

웹 앱 설치 및 홈 화면에 추가를 위한 태그
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<link rel="apple-touch-icon" href="아이콘 이미지 URL">
<link rel="manifest" href="manifest.json">

보안 및 권한 설정을 위한 태그
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
<meta name="referrer" content="no-referrer">
<meta name="robots" content="noindex, nofollow">

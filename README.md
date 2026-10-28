# einfollab.github.io — 아인폴랩 홈페이지 (HTML 버전)

PC에서 파일을 더블클릭해도, GitHub Pages에 올려도 같은 화면이 나오는 완성된 HTML입니다.

## 폴더 구성
- `index.html` — 홈
- `blog/index.html` — 블로그 글 목록
- `blog/*.html` — 블로그 글 (파일 하나가 글 하나)
- `assets/css/site.css` — 디자인 표준 2판 스타일 (모든 페이지 공통)
- `404.html` — 없는 주소 안내
- `robots.txt`, `sitemap.xml` — 검색엔진용
- `.nojekyll` — GitHub가 파일을 변환하지 않고 그대로 공개하게 하는 표시 (지우지 마세요)

## 새 블로그 글 올리기
1. `blog/` 안의 글 하나를 복사해 새 이름으로 저장합니다 (예: `blog/2026-11-dify-tips.html`, 영문·숫자·하이픈만).
2. 새 파일에서 `<title>`, 분류 태그(소식/블로그), 날짜, `<h1>` 제목, 본문(`ef-prose` 안)을 바꿉니다.
3. `blog/index.html`을 열어 `<ul class="ef-posts">` 바로 아래에 기존 `<li>` 하나를 복사해 맨 위에 붙이고, 링크·제목·날짜·설명과 `data-category`(소식 또는 블로그)를 바꿉니다.
4. 필요하면 `sitemap.xml`에 새 글 주소를 한 줄 추가합니다.

## 상단 메뉴 · 바닥글 · 문의 메일을 바꿀 때
모든 페이지에 같은 내용이 들어 있으므로, 바꿀 때는 `index.html`, `404.html`, `blog/` 안의 모든 파일에서 함께 바꿉니다.
(편집기의 "폴더 전체에서 찾아 바꾸기"를 쓰면 한 번에 됩니다.)

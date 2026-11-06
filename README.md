# web261104

준비물 (구할 자료)
1. 가져오기: 지난주 저장소의 index.html과 style.css 2개. 파일마다 브라우저에서 지난주 저장소의 파일
클릭 ⇒ 오른쪽 위 "Raw" 옆 복사 아이콘(Copy raw file, 안 보이면 "Raw"를 눌러 Ctrl+A, Ctrl+C) ⇒ VS
Code에서 같은 이름의 새 파일을 만들고 붙여 넣기.

2. 지난주 script.js는 가져오지 않고 브라우저에 열어 두기만 합니다. 배열 값(제목, 평점, 연도)을 데이터 파일 data.js로 옮겨 적고, 계산은 새 파일 app.js에 함수로 다시 씁니다.

3. 개봉일이나 poster_path 메모가 없으면 주소창에
https://api.themoviedb.org/3/search/movie?api_key=KEY&language=ko-KR&query=영화제목 ⇒ Pretty-print
체크 ⇒ results[0]의 release_date, poster_path 복사(자세한 절차는 6주차 안내문).
4. API 키는 주소창에서만 씁니다. index.html, data.js, app.js 어디에도 키를 적지 않습니다(저장소가 공개이기 때문입니다). 기말 프로젝트에서 키를 파일에 두는 방법을 따로 배웁니다.

지난주 것이 없으면 index.html은 ! + Tab 뼈대에 <h1>, 단계 1의 <pre>와 <script> 두 줄, 6주차 안내문의

TMDB 고지 푸터만 넣고 style.css는 빈 파일로 둡니다. 오늘 실습은 콘솔에서 하므로 충분합니다. 
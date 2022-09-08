# joinchart

다운로드 링크<br/>
<a href="https://drive.google.com/file/d/1kGN6Zzvg5O9z5hiQ7jU7na9lWLLjxOVL/view?usp=sharing">다운로드</a>
<br/>
해당 파일을 다운 받아 압축을 풀어서 이클립스 환경에서 실행시키시면 됩니다.

● JSP, Html, Css, JavaScript를 활용한 음원순위 종합 사이트 구현<br/>
- K-pop의 수요 증가와 함께 성장하는 한국의 음원사이트들의 순위를 모아서 보여줌으로써 한국에서 현재 유행하는 노래들을 한눈에 파악할 수 있도록 하고 싶었음.<br/>
<br/>
● 학습 목표<br/>
- 크롤링에 대한 이해<br/>
- 정적 / 동적 페이지에 대한 이해<br/>
- JSON, JSOUP, AJAX를 이용한 데이터 활용<br/>
- JSP의 활용과 Html, Css, JavaScript와의 연결과정 체험<br/>
<br/>
● 주요 기능<br/>
- 음원사이트 4개(멜론, 지니, 벅스, 플로)의 실시간 순위 및 바이브의 일간 순위를 자바를 통해 크롤링 하여 5개의 리스트로 보여주는 사이트를 제작.<br/>
  > 동적 데이터의 크롤링을 셀레니움을 통해서 하다보니 로딩에 1분에 가까운 시간이 소요됨. 이를 줄이기 위해서 AJAX를 활용하는 방식으로 변경, 로딩시간을 단축하는데 성공.<br/>
- 각 사이트의 실시간 또는 일간 순위, 및 곡 정보를 순위별로 기준 시간과 함께 보여주며, 페이징 구현과 검색기능 제공<br/>
- 멜론의 하루 동안의 순위 변화와 지니의 지난 3주간의 일간 순위를 볼 수 있는 차트 제공 (노래 제목을 클릭하면 사이트 이동)<br/>
- 브라우저 개발자 도구 활용<br/>
- 검색 등의 얻어낸 정보를 바탕으로 오픈소스를 사용<br/>
- CSS 작업을 통한 가시성 확보<br/>

타이틀 클릭시 <br/>
멜론 -> 실시간 차트<br/>
지니 -> 3주간 차트<br/>


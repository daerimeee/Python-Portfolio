프로젝트 이름: api를 활용한 코로나19 실시간 확진자 수 크롤링

프로젝트 설명:
이 프로젝트는 공공데이터 API를 활용하여 코로나19의 실시간 확진자 수를 수집하는 것이 목표입니다. 사용자는 특정 날짜와 기간을 입력하면, 해당 기간 동안의 확진자 수와 관련 정보를 수집할 수 있습니다.


사용된 기술 및 도구:

Python: 프로그래밍 언어로서, 데이터 수집과 처리를 위해 사용되었습니다. 
Pandas: 데이터 분석 및 처리를 위해 사용되었습니다.
Requests: 웹 페이지의 내용을 가져오는 데 사용되었습니다.
BeautifulSoup: 웹 페이지의 HTML을 파싱하는 데 사용되었습니다.


개발 과정:
사용자로부터 기준 년도, 월, 일, 그리고 크롤링 하고자 하는 기간을 입력 받습니다.
입력 받은 정보를 바탕으로 공공데이터 API에 요청을 보내 데이터를 수집합니다.
수집된 데이터는 BeautifulSoup를 통해 파싱하여 필요한 정보를 추출합니다.
추출한 정보 Pandas를 이용해 데이터프레임으로 변환되고, 이를 리스트에 추가합니다.


결과:
이 프로젝트를 통해, 사용자는 자신이 원하는 기간 동안의 코로나19 확진자 수와 관련된 정보를 실시간으로 수집할 수 있게 되었습니다. 
이를 통해, 코로나19의 추세를 파악하고, 기본 api를 활용하는데 있어서 도움이 되었습니다.

# 자바스크립트 코딩 연습

1. ## Startpage

- URL : http://sujikim.dothome.co.kr/
- 구현 기능
  - 오늘 날짜 (년/월/일)
  - 현재 시간(시:분)
  - 검색(네이버로 연결)
  - 배경색 변경 
  - 위치 기반 날씨 api ( openweathermap 사용 )
    - 보안 설정이 되어있지 않은 사이트에서는 HTML5 Geolocation api를 사용할 수 없다.
  - 투두리스트
  	- checked/ unchecked 기능
  	  - 새로고침 시에도 체크 사항 유지
  	- 삭제 기능 

 <img src="https://user-images.githubusercontent.com/47530310/58156584-652cc800-7cb1-11e9-9f19-9072d4e345e6.PNG" alt="위치설정전" width="50%">
------
 <img src="https://user-images.githubusercontent.com/47530310/58156692-a329ec00-7cb1-11e9-8a18-5d1461c037df.PNG" alt="위치설정후" width="50%">

2. ## Canvas API 그림판

- URL : http://sujikim.dothome.co.kr/templates/paint.html
- 구현 기능
  - 색상표
    - 배열과 [Change] 버튼 이용해 총 18가지 색 구현
    - 선택한 색상을 화면에 표시
  - 브러쉬로 그리기
    - 기본 색상 값은 색상표 div에 속한 첫 번째 자식 요소의 배경색으로 지정
    - 캔버스를 기준으로 mouseup 또는 mouseleave 이벤트 발생 시 그리기 중단
  - 브러쉬 크기 조절
    - input 태그 range value 값에 맞춰 브러쉬 크기 조절
    - range value값에 따라 색상표에서 선택된 색이 표시된 div의 width와 height값의 크기가 변경된다.
  - 전체 색칠하기
    - [Fill] 버튼 클릭 후 컨버스를 클릭하면 컨버스 전체에 색이 칠해진다.
    - 전체 색칠하기와 브러쉬로 그리기를 구분하기 위해 버튼의 innerText값을 [Fill]과 [Paint]로 구분
    - fillRect() 사용
  - 지우기
    - clearRect() 사용
  - 파일로 다운로드하기
    - png파일로 저장
    - 다운로드 파일명은 paint로 지정
  
  


> 참고 사이트
>
> - <a href="https://academy.nomadcoders.co/" target="_blank">노마드코더</a>


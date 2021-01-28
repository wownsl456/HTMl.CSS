# HTMl.CSS
HTML과 CSS

background-repeat 정리
background-repaet은 이미지를 반복시킬 것인지 아닐 것인지, 
그리고 반복시킨다면 어떤 방식으로 반복시킬 것인지 정해주는 속성이다.
																	
background-repeat: no-repeat; (반복하지 않음)
background-repeat: repeat-x; (가로 방향으로만 반복)
background-repeat: repeat-y; (세로 방햑으로만 반복)
background-repeat: repeat; (가로와 세로 모두 반복)
background-repeat: space; (반복할 수 있는 만큼 반복한 뒤, 남는 공간은 이미지 간의 여백으로 배분)
background-repeat: round; (반복할 수 있는 만큼 반복한 뒤, 남는 공간은 이미지 확대를 통해 배분)*/


/*background-size 정리
background-size는 배경 이미지의 사이즈를 정해주는 속성이다.
background-size: auto; (원래 이미지 사이즈대로 출력)
background-size: cover; (화면을 꽉 채우면서, 사진 비율을 유지) 
background-size: contain; (가로, 세로 중 먼저 채워지는 쪽에 맞추어서 출력) 
background-size: 30px 50px; (픽셀값 지정 가로:30px 세로:50px로 설정) 
background-size: 60% 70%; (퍼센트값 지정 가로:부모 요소 width의 60%, 
                          세로:부모 요소 height의 70% 설정)*/


/*background-position 정리
background-pisition은 배경 이미지의 위치를 정해주는 속성이다.
[아래단어와 같은 총 9개의 조합이 가능하다]
background-position: left top ;	
background-position: left center;
background-position: left bottom;
background-position: right top;
background-position: right center;
background-position: right bottom;
background-position: center top;
background-position: center center;
background-position: center bottom;
																	
background-position: 25% 75%; (퍼센트로 지정해주기 가로:전체 width의 25% 지점, 
															 세로:전체 height의 75% 지점)
background_position: 100px 200px; (픽셀로 지정하기) 
														가로:가장 왼쪽 가장자리에서 100px 이동한 지점,
														세로:가장 상단 가장자리에서 아래로 200pxa 이동한 지점)*/

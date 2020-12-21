# Fsoft_finalproject
사용자로부터 학년, 학과, 전공 수, A교시와 점심시간 선호, 영역별 교양 분야를 입력받아 수강시간표를 생성하는 프로그램

https://ho-ong.tistory.com/2?category=815308 에 있는 코드를 참고하여 작성함.
(참고한 코드의 프로그램과 입력되는 과목 데이터의 구조, 구현하는 프로그램의 기능이 다르므로 시간표 gui를 생성하는 부분과 이메일 오류 처리 부분만 참고함.)

필요한 패키지: pandas, xlrd, pillow, pyautogui, email6, csFIFO

<코드를 실행 시 주의사항>
1. data.xlsx 파일을 다운 받아 저장하고, new1.py의 convert_excel함수의 코드 중 엑셀파일의 저장위치를 작성하는 부분을 실제 파일의 저장위치로 수정해야 함.
2. gui1.py의 send_email 함수의 코드 중 보내는 이메일 주소와 비밀번호를 실제 이메일 주소와 비밀번호로 수정해야 함.(현재 올린 코드에는 임의의 gmail주소와 비밀번호가 들어가 있음.)
3. data 파일과 gui1.py, new1.py가 같은 폴더에 있어야 함.

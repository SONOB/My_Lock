# face_recognition_door

pip 해줄 파일들이 조금 많습니다. 중간중간 (y/n)이 나오면 y를 누르고 엔터를 치시면 됩니다.

$sudo apt-get update

$sudo apt-get upgrade

pip설치

$sudo apt-get install python3-pip


numpy, openCV설치

$sudo pip install numpy

$sudo pip install opencv-python


mysql 설치
MySql 8.0 이상 유저
pip install mysql-connector-python

하위 버전
pip install mysql.connector


dlib 설치
sudo pip install cmake

sudo apt-get install libatlas-base-dev

sudo pip install dlib
dlib의 경우 엄청난 시간이 걸리는데 그래도 설치가 안될경우 직접 라이브러리를 다운받아 설치하는 방법도 고려해 보시길 바랍니다.


lcd 사용 관련
터미널창에서 
sudo apt-get install python-smbus를 다운받고

i2cdetect -y 1 을 치면 행열로 연결된 숫자가 나오는데 저희의 경우 0x27이였습니다.

git clone https://github.com/eleparts/RPi_I2C_LCD_driver import를 위한 파일


카카오톡
카카오톡 관련한 부분은 다른 리포지토리 내 kakao파일을 확인해 작업 진행해 주시면 됩니다.
동일하게 josn파일을 만들기 때문에 json이름수정도 필수입니다.

키패드의 경우 국내에서 판매중인 제품은 맞지만 상품 상세설명에 있는대로 진행했을때 행열이 꼬일것입니다. 
그렇기 때문에 kepad.jpg에 있는(GPIO위치는 바꿔도 상관없음) 행열대로 선을 연결해야 버튼에 맞게 눌릴것 입니다.

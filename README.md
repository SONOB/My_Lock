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


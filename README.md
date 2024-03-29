## 얼굴인식 도어락 

사용장치 
- Raspberry Pi4
- Camera Module V3 

사용 언어 
- Python 
- Java

개발 환경 
- VScode 
- Android Studio
- MariaDB

요약  
- 라즈베리파이를 활용하여 얼굴인식을 진행하여 도어락을 제어, 어플을 사용하여 원격으로 도어락 제어가능 
- Unknown이 감지되면 어플을 통하여 알림 
- 도어락의 동작에 따라 로그가 남게되고 이를 어플을 통해 확인가능
- 얼굴 인식의 데이터 객체는 파이썬의 pickle을 활용하여 저장
- 새로운 사람을 추가할경우에는 동영상을 업로드하면 영상을 프레임단위로 쪼개서 사진으로 변환시킨후 이를 학습
  
구조

<img src="https://github.com/Kuan29/face_recognition/assets/88146943/2d7e6cbd-7ec0-431b-a6a1-780099543e99"  width="400" height="300"/>

구현화면 및 얼굴인식

<img src="https://github.com/Kuan29/face_recognition/assets/88146943/24bbb1e1-0340-4c9e-8814-b9d596e4e147"  width="200" height="400"/>
<img src="https://github.com/Kuan29/face_recognition/assets/88146943/d32be923-2fc0-4309-9854-bd2a0b02f32f"  width="200" height="400"/>
<img src="https://github.com/Kuan29/face_recognition/assets/88146943/2c6a3af9-8787-4905-87d9-bb7dd0a03956"  width="200" height="400"/>
<img src="https://github.com/Kuan29/face_recognition/assets/88146943/bbc193ac-c059-482f-b0bd-971ade831c42"  width="200" height="400"/>
<img src="https://github.com/Kuan29/face_recognition/assets/88146943/148bb99b-e2e1-4fd4-a807-8c45a81e6d54"  width="200" height="400"/>
<img src="https://github.com/Kuan29/face_recognition/assets/88146943/449b39e3-cb34-47c9-ab2b-2288cda04cbd"  width="200" height="250"/>





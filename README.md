# Dormitory visit system using VR

## 소개
* 2차원의 사진은 단면적인 모습만 보이기에 실제와 동일한지 확인 불가능
* 혼란을 야기하지 않고 잘못된 정보습득 방지
* 360도 카메라를 이용해 VR 서비스 제공하는 점은 기숙사 VR 시스템과 차이가 있음

## 제안모델
* Gear VR
  * VR Header는 스마트폰과 C-type USB 단자로 연결되며 사용자가 VR 환경을 볼 수 있게 
  * VR Remote Controller는 VR 환경상에서 클릭 등의 상호작용가능
  
* Unity Virtual Player Device
  * VR환경이 실행되는 본체
  * VR환경을 실행시켜주는 Oculus Application, Unity Application
  * Gyroscope Sensor를 통해 VR 헤드 트래킹 기능 수행

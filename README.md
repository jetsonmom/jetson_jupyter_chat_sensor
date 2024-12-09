#### jetson_jupyter_chat_sensor
```
!pip install pyserial
!pip install pandas matplotlib

```
####가상 환경을 비활성화하고, 시스템에서 필요한 패키지를 설치합니다.
```
deactivate  # 가상 환경을 종료
sudo apt update  # 패키지 목록을 업데이트
sudo apt install libbz2-dev  # bz2 관련 개발 라이브러리 설치
```
#### 가상 환경 활성화 후 필요한 패키지를 다시 설치합니다.
```
source myenv/bin/activate  # 가상 환경 활성화
pip install pandas matplotlib  # 패키지 설치

```

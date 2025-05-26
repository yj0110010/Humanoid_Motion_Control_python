# HumanoidMotionControl_python

 이 프로젝트는 이전에 만들었던 pothole_yolo 애플리케이션을 활용하여 휴머노이드 로봇을 제어하는 애플리케이션 입니다. YOLOv5 모델을 이용해 실시간으로 **도로 포트홀(pothole)**을 감지하고, 감지 시 자동으로 휴머노이드 모션을 실행합니다.

## 주요 기능
 - 웹캠으로 실시간 이미지 캡처

 - 학습된 YOLOv5 모델을 통한 포트홀 탐지

 - 탐지된 포트홀 이미지 저장 기능

 - 사용자가 버튼 클릭으로 휴머노이드에 모션 명령 전송

 - 포트홀 탐지 시 자동으로 휴머노이드에 특정 모션 실행


## 사용용방법
### 1. 깃허브 리포지토리 가져오기
#### yolov5
 - https://github.com/ultralytics/yolov5.git
#### HumanoidMotionControl_python
 - https://github.com/Emmett6401/humanoidMotionControl_python

### 2. CP2104 드라이버 설치하기 
 - https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads

### 3. miniconda를 이용해 가상환경 생성하기 (파이썬 3.9)

### 4. 의존성 설치하기 
 - pip install -r requirements.txt

### 5. app.py 실행


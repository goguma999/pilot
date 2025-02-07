# ML/DL STUDY
## ML 
---

## DL 
### mnist 필기체 데이터 분류 | Tensorflow | CNN
- Data: Tensorflow에 내장된 mnist 필기체 데이터
- model 1: FC3층/SGD -> acc: 0.9346 - loss: 0.2425
- model 2: FC3층/SGD/BatchNormalization/Dropout/Earlystop -> acc: 0.9894 - loss: 0.0341
🔗 [코드](DL/DL_mnist_CNN.ipynb)


### 닮은꼴 배우 조우진 vs 김병철 분류 | Tensorflow | VGG19
- Data: 구글 이미지 스크래핑으로 배우 별 100장 수집
- model 1: VGG19+FC3층 -> acc: 0.9290 - loss: 0.1860
- model 2: VGG19+FC3층/검증데이터분리/데이터증강/합성곱층 고정/뉴런(128,64)/Adam학습률o -> acc: 0.6940 - loss: 0.6225
- model 3: VGG19+FC3층/검증데이터분리/데이터증강/뉴런(128,64)/Adam학습률x 
🔗 [코드]()


### 유동인구 카운트 YOLO 영상 파일럿 프로젝트
- **프로젝트 설명**: YOLO 모델을 사용하여 영상 속 유동인구를 실시간으로 감지하고, 입장 및 퇴장 수를 카운트하는 시스템.
- **주요 기능**: 사람 객체 탐지, 입장 및 퇴장 카운팅, 누적 인원 계산
🔗 [코드](https://colab.research.google.com/drive/1g1eJ_ly3gkeQ5JVrr_86XQi1GimkRnyH?usp=sharing)
- **시연 이미지**:  
![시연 이미지](https://github.com/goguma999/pilot/blob/main/count/sjk.jpg?raw=true)




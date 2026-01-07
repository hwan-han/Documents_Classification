# CV 경진대회                  

## 1. Competiton Info

### Overview

- 의료·금융·보험·물류 등 다양한 산업에서 대량의 문서 이미지를 자동으로 식별, 처리하기 위해 활용되는 CV 분야의 핵심 태스크인 문서 타입 이미지 분류(Image Classification) 문제를 다룹니다.


## 2. Components

### Directory


```
├── Limhwanseok
│   ├── augmentation.ipynb 
│   ├── image_vision.ipynb
│   └── swin_large_augmentation.ipynb 
   
```

## 3. Data descrption

### Dataset overview
전반적인 데이터셋의 이미지들 확인 
FiftyOne 이용
다른 클래스의 이미지와의 레이아웃 키워드 차이 확인

<img width="928" height="361" alt="image" src="https://github.com/user-attachments/assets/285f3bf2-34a4-4e63-b7ff-79ca431deebb" />




### EDA

train datasets 이미지 레이아웃 확인 
객체 이미지 + 문서이미지
대부분 캡쳐본으로 깨끗하고 노이즈가 많이 없는 상태

test datasets 이미지 레이아웃 확인
회전, 반전, 흐림, 이미지 혼합(섞임), 잘림 등 다양한 유형의 노이즈 및 변형 포함

<img width="1033" height="264" alt="image" src="https://github.com/user-attachments/assets/496940bc-3746-4f05-8adf-4763daafb983" />


## 4. Modeling

### Model descrition

- ViT (Swin Large, 384)
  

### Modeling Process


<img width="1222" height="412" alt="image" src="https://github.com/user-attachments/assets/3edeeb48-64c1-49a3-95a6-72384e785882" />

<img width="1229" height="548" alt="image" src="https://github.com/user-attachments/assets/53ff7ac9-d956-4b17-9011-ec17ef36e74f" />

<img width="1253" height="546" alt="image" src="https://github.com/user-attachments/assets/07f6d9ad-d28f-4ed3-bbd6-b9458f285878" />

<img width="1180" height="541" alt="image" src="https://github.com/user-attachments/assets/bf103408-6895-4e71-a97a-ebab3a728ace" />



## 5. Result

### Presentation

- https://docs.google.com/presentation/d/1AdBPM1qlEKxrxkfW6FrzrgiNRj-qfuXR/edit?pli=1&slide=id.g399552807a2_2_70#slide=id.g399552807a2_2_70


<img width="898" height="116" alt="image" src="https://github.com/user-attachments/assets/a5b92de6-fa7f-435c-9068-430838b6a3c6" />







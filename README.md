# Challenge 2(Scene Text Recognition)

## 동영상 Link
LINK: https://www.youtube.com/watch?v=IwxWccxEanw

## Scene Text Recognition
STR은 사람들이 활동하고 있는 환경에서 카메라, 센서 등으로 기록한 이미지에 포함되어 있는 이미지속의 문자를 인식하는 알고리즘임 

![image](https://user-images.githubusercontent.com/71881396/143402753-3bbf9256-59fa-48a6-9a5b-63ab65f2fa83.png)


## Model Architecture

![image](https://user-images.githubusercontent.com/71881396/143402185-f9961afe-ddd9-4eb4-bb2e-ba319c2c8f1b.png)

## Model size

본 challenge에서 참고한 논문에서는 세가지 모델을 제공합니다. 
처음에 Tiny size의 모델을 사용했을 경우 challenge baseline을 넘지 못한 관계로 Small size의 모델을 사용해 코드를 다시 돌렸습니다. 
실험결과 Small size Model을 사용했을 경우 Challenge baseline을 넘었습니다. 

![image](https://user-images.githubusercontent.com/71881396/143402222-db47a5b6-541e-490a-b5bf-c89a60f7f678.png)

### Tiny size Model VS Small size Model

![image](https://user-images.githubusercontent.com/71881396/143402632-d50be64a-0f42-44f7-bb34-e669438cb030.png)


## 훈련과정

![image](https://user-images.githubusercontent.com/71881396/143402506-fb3e1140-93f9-42c4-900b-eb1c0c28e0fa.png)

## Challenge baseline 찍기 
![image](https://user-images.githubusercontent.com/71881396/143406421-acde4e59-7490-4174-9eca-db3e2fc83ea8.png)

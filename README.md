# SegmentationModeling [2022.05.15 ~ 2022.06.15]
## 데이크루 2기, 두번째 프로젝트 
### 멤버 : 이정환(프로젝트 팀장), 강수연, 이태범, 전다운, 허지혜

1. U-NET을 이용한 segmentation 결과보기
  - 데이터 Augmentation 기법을 세 가지로 진행
    - 어떠한 Augmentation 적용을 하지 않은 데이터
    - 논문에 있는 Augmentation인 Overlap-tile, center crop 적용 데이터
    - OpenCV Gaussian Blur 적용 데이터
    
2. RES U-NET을 이용한 segmentation 결과보기
  - 데이터 Augmentation 기법을 세 가지로 진행
    - 어떠한 Augmentation 적용을 하지 않은 데이터
    - 논문에 있는 Augmentation인 Overlap-tile, center crop 적용 데이터
    - OpenCV Gaussian Blur 적용 데이터    

3. RPA RES U-NET을 이용한 segmentation 결과보기
  - 데이터 Augmentation 기법을 세 가지로 진행
    - 어떠한 Augmentation 적용을 하지 않은 데이터
    - 논문에 있는 Augmentation인 Overlap-tile, center crop 적용 데이터
    - OpenCV Gaussian Blur 적용 데이터 
    
### 결과
![image](https://user-images.githubusercontent.com/64202709/188083550-5fa058c4-efde-42f1-960c-738619258764.png)

결과 판단척도 : IOU(Intersection of Union)

### 결론
- U-NET 논문에서 적용했던 Augmentation 기법을 적용하는 것이 가장 좋은 결과값을 가지고 왔다.
- 여러 기법을 적용해서 다양한 결과를 얻었다.

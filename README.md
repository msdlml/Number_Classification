## 숫자 이미지 분류 프로젝트
-----------------------------------------------------
### 프로젝트 배경
![image](https://github.com/msdlml/Number_Classification/assets/156978979/a4dad4c7-1911-4539-af14-3055b4ddc036)
![image](https://github.com/msdlml/Number_Classification/assets/156978979/700656f2-98b8-4fa2-8ffd-018fbdc7d4d5)

### 프로젝트 수행절차
![image](https://github.com/msdlml/Number_Classification/assets/156978979/918d790b-10a5-402d-bc58-7bc6a1fc9c9f)
![image](https://github.com/msdlml/Number_Classification/assets/156978979/fd4f8fd9-7fb5-4c2c-bcc5-f37f26f3b320)

### 데이터 전처리
- 스탠포드에서 제공하는 데이터의 포맷 중, 첫번째 포맷을 활용하여 새롭게 추출한 이미지를 사용해 모델의 성능을 높임
- 1개의 이미지에 하나의 숫자가 크롭되도록 csv파일 전처리
- mat 파일을 csv파일로 변환 후 단일 숫자 이미지로 크롭한 뒤 32*32로 리사이징
- 이미지의 양이 많아 협업 시 불편함을 느껴, 픽셀 데이터(nparray)로 변환하여 저장

### 모델 튜닝 및 평가
![image](https://github.com/msdlml/Number_Classification/assets/156978979/3686b27b-d7d0-44e8-8cce-b4eb68ec9870)
![image](https://github.com/msdlml/Number_Classification/assets/156978979/e1340ce0-4d0c-4b76-9bc5-6fffd65edba7)
![image](https://github.com/msdlml/Number_Classification/assets/156978979/5fb9b854-0071-4d64-99d5-59320fb13b84)

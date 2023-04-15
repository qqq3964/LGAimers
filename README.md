# LGAimers

### 대회 정보
```
lgaimers 대회에서 스마트 공정 품질 예측대회
```
데이터 정보 및 Label 정보 Y_Class 가 Lable이다.
```
PRODUCT_ID : 제품의 고유 ID
Y_Class : 제품 품질 상태(Target) 
0 : 적정 기준 미달 (부적합)
1 : 적합
2 : 적정 기준 초과 (부적합)
Y_Quality : 제품 품질 관련 정량적 수치
LINE : 제품이 들어간 공정 LINE 종류 ('T050304', 'T050307', 'T100304', 'T100306', 'T010306', 'T010305' 존재)
PRODUCT_CODE : 제품의 CODE 번호 ('A_31', 'T_31', 'O_31' 존재)
X_1 ~ X_3326 : 공정 과정에서 추출되어 비식별화된 변수
```
모델
```
autogluon
```
데이터셋
```
스마트 공정 품질 데이터셋
```
### 최종 등수 500팀중 10등 [LeaderBoard](https://dacon.io/competitions/official/236080/leaderboard)

<p align="center"><img src="https://user-images.githubusercontent.com/97833069/232242074-fab856ee-c736-4af4-8ae8-3595645eae41.png"></p>

```
대회 성적 Dacon
```

![image](https://user-images.githubusercontent.com/97833069/232241969-a12cf855-48c0-4e41-a40b-1f0686ef7c44.png)

# Prediction of FIFA Transfer Fee (Dacon)

*만약 위 파일의 로딩에 실패한다면

- [FIFA_version1](https://nbviewer.jupyter.org/github/PingPingE/FIFA_Transfer_Fee/blob/master/FIFA_v1.ipynb")
- [FIFA_version2](https://nbviewer.jupyter.org/github/PingPingE/FIFA_Transfer_Fee/blob/master/FIFA_v2.ipynb")

## 목적 및 목표
현재 선수를 매각 혹은 영입하려는 구단은, 구단 내 스카우터를 파견합니다. <br>
스카우터는 선수의 능력치를 수집하고 이를 통해 구단에 어느정도 가격(유로)을 측정하면 좋을지 보고를 하게 됩니다.<br>
FIFA에서 제공하는 데이터를 바탕으로 선수의 시장가격과 능력치 사이의 상관성을 알아보고자 합니다.

## 제공 데이터
- FIFA_train.csv : 축구선수의 정보와 능력치 그리고 이적시장 가격(value)이 포함된 데이터
- FIFA_test.csv : 축구선수의 정보와 능력치가 포함된 데이터
- submission.csv : 답안지의 형식

## 평가 지표
- RMSE

## 현재 최고점(최저 RMSE)
- 853212.18 (2020.08.28 기준 상위 20%)

## 파일
- FIFA_v1: 전체 데이터 시각화 및 분석 + 다양한 기법 적용 -> 결과는 results.csv
- FIFA_v2: v1을 기반으로 모델링에 집중한 작업물 -> 결과는 results2.csv

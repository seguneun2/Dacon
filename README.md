### Dacon 대구시 빅데이터 분석 경진대회 - 에너지 분야 

**배경**
- 늘어나는 폐기물에 따른 환경오염과 매립지 부족
- 폐기물에서의 자원순환의 중요성 (재사용, 재활용, 에너지 회수, 에너지 감소) 

**분석 목적**
- 폐기물 처리 현황을 분석함으로써 폐기물 관리의 효율성을 높이고, 지속 가능한 자원순환 도시로 발전할 수 있는 전략을 수립하고자 함 

**사용데이터**
- 전국 폐기물 발생 및 처리현황 오픈데이터

**분석기법**
ETC / XGBoost : 폐기물 처리 기관의 여러 특성을 바탕으로 폐기물 처리 효율을 예측
SHAP : 각 feature가 모델의 예측에 얼마나 기여했는지 계산하기 위해 사용
Correlation 계수 : 최종 매립 및 에너지 회수에 영향을 주는 폐기물 종류 분석

**분석결과**
- 폐기물 처리 과정 중 재활용 과정에 대한 분석
![image](https://github.com/user-attachments/assets/93b919a5-1dee-4ddb-91d0-7672ca8320b9)

- 소각 시설의 총 효율에 미치는 요소 분석
![image](https://github.com/user-attachments/assets/9f3abdbb-5d87-4c49-97c3-c7c51b4434eb)

- 폐기물 발생량과 매립비율 사이의 상관계수 분석
![image](https://github.com/user-attachments/assets/f4cb9b41-fbdc-4022-975b-f5eacf3d2b2f)

- 폐기물 발생량과 에너지 회수 사이의 상관계수 분ㅅ거
![image](https://github.com/user-attachments/assets/82eab06b-c619-4e2b-94b7-a4b5ee16c7f1)

- 자세한 내용은 발표자료 참고

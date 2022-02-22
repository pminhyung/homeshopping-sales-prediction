# NS SHOP+ 판매실적 예측을 통한 편성 최적화 방안(모형) 도출
## [빅콘테스트 2020](https://www.bigcontest.or.kr/introduce/summary.php) (2020. 8. 14 ~ 2020. 9. 28) 
  
**팀명: InsightOut (박민형, 김우용, 박서희, 문찬호)**  
  
**(설명 하단에 발표자료 포함)**  

**[판매실적 예측 모델개발의 의의]**  
- 홈쇼핑의 경우 방송편성 스케줄이 수익을 결정한다고 할 수 있습니다. 상품의 종류, 브랜드, 가격 등에 따라 특정시간대 혹은 요일에 대해 방송했을 때 기대 수익은 상이합니다
- 기존 데이터를 바탕으로 여러 조건에 따른 매출 발생 패턴을 분석하고, 이를 바탕으로 매출 예측 모델을 개발하여 편성표를 최적화한다면, 수익 극대화로 이어질 수 있습니다. 해당 대회는 매출 극대화를 위한 포스트 코로나 기간의 NS SHOP+ 판매 실적 예측모형을 개발하고 , 편성 계획 수립한다는 점에서  의의가 있습니다

**[최종 모델 성능]**  
- 2019년 1월 ~ 12월 데이터 학습 및 2020년 6월 판매실적 예측
- **Average val MAPE : 0.4048** (대회 1등 모델 MAPE : 0.3701)
  
**[제공데이터 설명]**  
- Train 데이터 (2019.01.01 ~ 2019.12.31) 38311개
- Test 데이터 (2020.06.01 ~ 2020.06.30) 2893개
- 변수 : 방송일시, 노출(분), 마더코드, 상품코드, 상품명, 상품군, 판매단가, 취급액(Target)
  
**[최종 사용 모델]**  
LightGBM : Boosting + GradientDescent + Regularization 로 이루어진 XGBoost 모델에 연산 병렬처리를 통해 학습시간을 단축한 모델
  
**[프로젝트 결과 보고서]**

<img src = '/assets/slide1.PNG'>
<img src = '/assets/slide2.PNG'>
<img src = '/assets/slide3.PNG'>
<img src = '/assets/slide4.PNG'>
<img src = '/assets/slide5.PNG'>
<img src = '/assets/slide6.PNG'>
<img src = '/assets/slide7.PNG'>
<img src = '/assets/slide8.PNG'>
<img src = '/assets/slide9.PNG'>
<img src = '/assets/slide10.PNG'>
<img src = '/assets/slide11.PNG'>
<img src = '/assets/slide12.PNG'>
<img src = '/assets/slide13.PNG'>
<img src = '/assets/slide14.PNG'>
<img src = '/assets/slide15.PNG'>
<img src = '/assets/slide16.PNG'>
<img src = '/assets/slide17.PNG'>
<img src = '/assets/slide18.PNG'>
<img src = '/assets/slide19.PNG'>
<img src = '/assets/slide20.PNG'>
<img src = '/assets/slide21.PNG'>
<img src = '/assets/slide22.PNG'>
<img src = '/assets/slide23.PNG'>
<img src = '/assets/slide24.PNG'>
<img src = '/assets/slide25.PNG'>
<img src = '/assets/slide26.PNG'>
<img src = '/assets/slide27.PNG'>
<img src = '/assets/slide28.PNG'>
<img src = '/assets/slide29.PNG'>
<img src = '/assets/slide30.PNG'>
<img src = '/assets/slide31.PNG'>
<img src = '/assets/slide32.PNG'>

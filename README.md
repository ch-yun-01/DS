# DS를 위한 통계적 방법론 - HW04

본 과제에서는 이전 연구(HW01~HW03)의 분석 결과를 바탕으로, 정신건강 데이터의 통계적 특성과 기계학습 모델 적용 가능성을 검토하였다. 사용한 데이터는 스위스 로잔 대학교 의과대학 학생들의 정신건강 관련 설문 데이터이다.  
(데이터 출처: [Zenodo](https://zenodo.org/record/5702895))

### 연구 요약
- **HW01**: 부정적 감정(우울, 불안, 소진)의 강한 상관관계 → 복합적인 정신건강 문제 발생 가능성 시사  
- **HW02**: 성별에 따른 차이  
  - 여성 의대생: 부정적 감정 평균이 남성보다 높음, 우울·불안에서 유의미한 차이  
  - 여성 의대생: 공감 능력(행동, 인지, 정서)도 더 높음  
  - 남성 의대생: 전문직 스트레스 지수가 더 높음  
  - 우울 지수 높은 그룹은 행동적 공감 능력이 특히 낮음  
- **HW03**: 나이브 베이즈 분류  
  - 감정 데이터 포함 → 성능 향상  
  - 그러나 임상 실용성 측면에서는 감정 데이터를 제외한 모델이 더 유용할 수 있음

### 향후 연구
- 감정 데이터를 배제한 우울증 예측 모델의 성능 향상 필요  
- 임상 환경에서 환자의 우울증을 효과적으로 감지·대응할 수 있는 도구로 확장 가능

# Statistical Methods for Data Science - HW04

This assignment builds on previous analyses (HW01–HW03), exploring statistical characteristics of mental health data and the application of machine learning models.  
The dataset was obtained from medical students at the University of Lausanne, Switzerland.  
(Data source: [Zenodo](https://zenodo.org/record/5702895))

### Summary of Previous Studies
- **HW01**: Strong correlations were observed among negative emotions such as depression, anxiety, and burnout. These findings suggest the potential for interconnected mental health problems.  
- **HW02**: Gender differences in mental health indicators were investigated.  
  - Female medical students: higher averages in depression and anxiety, and higher empathy (behavioral, cognitive, and emotional).  
  - Male medical students: higher levels of stress related to the medical profession.  
  - Students with high depression scores: lower empathy, especially in behavioral empathy.  
- **HW03**: A Naïve Bayes classifier was applied to predict individuals with high vs. low clinical risk of depression.  
  - Performance improved when emotional data were included.  
  - However, from a practical perspective, models that exclude emotional data may be more useful in clinical contexts.

### Future Directions
- Developing depression prediction models that perform well **without relying on emotional data**.  
- Such approaches could provide more practical and effective tools for early detection and intervention in clinical environments.

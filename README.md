# kaggle_playground_predicting_heart_disease-26.2-
kaggle playground (26-2)

### 📌 프로젝트 개요
- **목표:** 환자의 건강 데이터를 바탕으로 심장병 유무(Presence/Absence)를 예측
- **데이터셋:** Kaggle Playground Series - Feb 2026
- **주요 성과:** Decision Tree부터 AutoGluon까지 다양한 모델 실험

### 🛠️ 사용 기술 및 모델
- **Library:** Pandas, Scikit-learn, XGBoost, LightGBM, AutoGluon
- **Modeling Strategy:**
  - **Baseline:** Decision Tree & Random Forest (성능 비교 기준 설정)
  - **Boosting:** XGBoost, LightGBM (고성능 분류 모델 활용)
  - **Ensemble:** Voting Classifier를 통한 모델 결합
  - **AutoML:** **AutoGluon(TabularPredictor)**을 활용한 최적의 앙상블 조합 탐색

### 📈 실험 결과
- **Best Model:** AutoGluon (WeightedEnsemble_L2)
- **Evaluation Metric:** Accuracy (약 88.7% 달성)

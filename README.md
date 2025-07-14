# 🚗 DaySchool 자동차 보험 사기 탐지 해커톤 프로젝트

이 프로젝트는 데이 스쿨 기초 트랙 2025 해커톤의 일환으로 진행되었으며, **자동차 보험 사기를 효과적으로 탐지하는 머신러닝 모델을 개발**하는 것을 목표로 합니다. 주어진 데이터를 활용하여 사기성 보험 청구를 예측하고, 보험 회사의 손실을 줄이는 데 기여하고자 합니다.

---

## ✨ 주요 기능 및 특징

* **데이터 전처리**: 결측치 처리, 범주형 변수 인코딩 등 머신러닝 모델 학습에 적합하도록 데이터를 가공합니다.
* **EDA (탐색적 데이터 분석)**: 데이터의 분포, 변수 간의 관계 등을 시각적으로 분석하여 인사이트를 도출합니다.
* **피처 엔지니어링**: 모델의 예측 성능을 향상시키기 위해 새로운 피처를 생성합니다.
* **다양한 머신러닝 모델 활용**: 로지스틱 회귀, XGBoost, LightGBM 등 다양한 분류 모델을 적용하여 성능을 비교합니다.
* **모델 평가**: Accuracy, F1-Score, ROC-AUC 등 다양한 평가지표를 사용하여 모델의 성능을 정량적으로 분석합니다.

---

## 🛠️ 사용된 기술 스택

* **언어**: Python
* **라이브러리**:
    * 데이터 처리: `pandas`, `numpy`
    * 데이터 시각화: `matplotlib`, `seaborn`
    * 머신러닝: `scikit-learn`, `RandomForest`, `lightgbm`

---

## 🚀 설치 및 실행 방법

이 프로젝트를 로컬 환경에서 실행하려면 다음 단계를 따르세요.

1.  **저장소 클론**:
    ```bash
    git clone [https://github.com/jhkr1/DaySchool-Vehicle-InsuranceFraud-Detection-Hackathon.git](https://github.com/jhkr1/DaySchool-Vehicle-InsuranceFraud-Detection-Hackathon.git)
    cd DaySchool-Vehicle-InsuranceFraud-Detection-Hackathon
    ```
2.  **가상 환경 설정 (권장)**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Windows: .\venv\Scripts\activate
    ```
3.  **필요한 라이브러리 설치**:
    ```bash
    pip install -r requirements.txt
    ```
    * **참고**: 만약 `requirements.txt` 파일이 저장소에 없다면, `데이_스쿨_기초_트랙2025_자동차_보험사기_탐지_해커톤.ipynb` 노트북 파일 내 `import` 문을 확인하여 필요한 라이브러리들을 수동으로 설치해야 합니다. (예: `pip install pandas scikit-learn xgboost lightgbm matplotlib seaborn tqdm`)

4.  **Jupyter Notebook 실행**:
    ```bash
    jupyter notebook 데이_스쿨_기초_트랙2025_자동차_보험사기_탐지_해커톤.ipynb
    ```
    브라우저에서 노트북 파일이 열리면 셀을 순서대로 실행하며 분석 과정을 확인할 수 있습니다.

---

## 📊 데이터셋

이 프로젝트는 자동차 보험 사기 탐지를 위한 특정 데이터셋을 활용합니다. 데이터셋은 보험 청구 정보와 관련된 다양한 피처를 포함하며, `Is_Fraud` 컬럼이 사기 여부를 나타냅니다.

* `train.csv`: 모델 학습에 사용되는 데이터
* `test.csv`: 모델 예측에 사용되는 데이터
* `sample_submission.csv`: 제출 양식 예시

---

## 📈 결과 및 인사이트


* **최종 모델 성능**: RandomForest 모델이 F1-Score 0.358, Private Score 0.57981를 달성하며 현재 데이콘 리더보드 2등에 위치하고 있습니다.

---

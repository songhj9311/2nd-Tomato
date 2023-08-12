## 2nd-Tomato
국내 스마트팜 도입을 위한 AI기반 토마토 생체정보 모니터링 시스템 및 품질 예측 모델 개발
<br>
## 📚 사용언어 및 모듈
<a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/></a>
<a href="https://jupyter.org/" target="_blank"><img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white"/></a>
<a href="https://www.tensorflow.org/?hl=ko" target="_blank"><img src="https://img.shields.io/badge/Tensorflow-FF6F00?style=flat&logo=tensorflow&logoColor=white"/></a>
<a href="https://keras.io/" target="_blank"><img src="https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white"/></a>
<a href="https://scikit-learn.org/stable/index.html" target="_blank"><img src="https://img.shields.io/badge/Scikitlearn-F7931E?style=flat&logo=Scikitlearn&logoColor=white"/></a>
<a href="https://numpy.org/" target="_blank"><img src="https://img.shields.io/badge/Numpy-013243?style=flat&logo=numpy&logoColor=white"/></a>
<a href="https://pandas.pydata.org/" target="_blank"><img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white"/></a>
<a href="https://www.r-project.org/" target="_blank"><img src="https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white"/></a>
<a href="https://www.r-project.org/" target="_blank"><img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white"/></a>
<a href="https://www.r-project.org/" target="_blank"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=PyTorch&logoColor=white"/></a>

<br>

#### 1) 품질예측 모델
    - 환경데이터를 통해 품질(당도, 산도, 과중)을 예측하는 모델 구상
    - 데이터의 결측치에 대한 다양한 접근(Simple Imputation, KNN Imputation, Multivariate feature Imputation 등) 및 이상치 허용기준을 확립해 다양한 데이터 셋 구성
<div align = "center">
    <img src = "https://github.com/naleetwo/FinalProject/assets/127948197/6b1bbcd2-509a-4604-9a44-fcbb2bbc05f8" width = "680" height = "380"/>
</div>
<br>

    - 준비한 데이터 셋에 다양한 ML 회귀모델(KNN, Linear, Lasso, Ridge, SVR 등) 테스트를 통한 최적 모델 탐색
<div align = "center">
    <img src = "https://github.com/naleetwo/FinalProject/assets/127948197/372e9c21-4d62-46e0-bdca-c868931bdaa2" width = "680" height = "380"/>
</div>
<br>

    - 「과중·당도 ML 예측모델」회귀 예측모델생성
<div align = "center">
    <img src = "https://github.com/naleetwo/FinalProject/assets/127948197/2af95d0c-b8d5-4fd9-8ddb-06fa61d4a5da" width = "680" height = "380"/>
</div>
<br>


    - 「산도 DLL 분류모델」생성 * 카테고리화된 산도 Label 고려
<div align = "center">
    <img src = "https://github.com/naleetwo/FinalProject/assets/127948197/70bb74ee-3c93-48ef-9c4a-92ddf690a647" width = "680" height = "380"/>
</div>
<br>

#### 2) 질병 진단 모델
    - 「질병진단 모델 훈련 결과」
<div align = "center">
    <img src = "https://github.com/naleetwo/FinalProject/assets/127948197/5b2d687b-4dfb-4db8-ac34-c84f94225051" width = "680" height = "380"/>
    <img src = "https://github.com/naleetwo/FinalProject/assets/128697640/a478e8be-7348-439b-a98c-0b9a4e3658f7" width = "400" height = "380"/>
    <img src = "https://github.com/naleetwo/FinalProject/assets/127948197/5a2d9fd5-c081-4f8d-88e4-c1d68d9ea2b7" width = "600" height = "380"/>
</div><br>

#### 3) 생장 예측 모델
    - 「생육단계 판단 모델 훈련 결과」
<div align = "center">
    <img src = "https://github.com/naleetwo/FinalProject/assets/127948197/7efbe451-cee1-499e-a26c-6a72e9725312" width = "680" height = "380"/>
    <img src = "https://github.com/naleetwo/FinalProject/assets/127948197/1c9f186c-0cea-4c70-8c32-cb0d39b45332" width = "680" height = "380"/>
</div><br>

#### Web 서비스 구현
    - 웹 서비스 이용 시연
<div align = "center">
    <img src = "https://github.com/naleetwo/FinalProject/assets/127948197/991686e4-ed64-4d21-be44-5c9df3509a56" width = "680" height = 

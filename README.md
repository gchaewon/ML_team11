# ML_team11
Machine Learning (01) team 11 Team project

olab 런타임 오류로 인해서 data preprocessing 과정은 local laptop (RAM 16GB) 환경에서 진행하였습니다.
이후 전처리를 거친 데이터를 csv 파일로 저장하여, 다른 실험에 사용하였습니다. 

preprocess.ipynb 파일만 다운로드 받아서 수행해주세요. 

실제로는 전체 과정을 로컬 환경에서 수행해보았으나, 코드를 돌려보는 과정이 번거롭고 로컬 환경에서 수행하려면 필요한 패키지를 전부 다운받아야하는 문제가 있으므로, 

preprocess을 제외한 다른 실험 노트북 파일은 colab 환경에서 수행할 수 있도록 수정했습니다. 

### 1. preprocessing branch > preprocess.ipynb

Bash terminal
```
cd Desktop
git clone -b preprocessing --single-branch https://github.com/gchaewon/ML_team11.git
cd ML_team11
ML_team11 파일 내부의 preprocess.ipynb 파일을 열어 실행

``` 
### 2. Main brach
각 파일을 클릭 > open in colab 클릭  colab에서 실행 가능 

```preprocess.ipynb```:  데이터 전처리 (결과 포함, colab 실행 X)

```model_tranning.ipynb```:  모델 학습 및 정확도 실험 

```experiment_open_multi.ipynb``` : open world의 multiclassification 환경 모델 튜닝 & 평가 실험

```experiment_open_bi.ipynb```: open world의 binary classification 모델 튜닝 & 평가 실험

```experiment_open_closed.ipynb```: closed world의 multi classification 환경 모델 튜닝 & 평가 실험

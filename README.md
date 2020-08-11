# 삼성 대화시스템 실습자료

- 이 실습자료는 8월 13일, 8월 20일에 진행될 삼성 AI-Expert 과정 실습을 위해 제작된 자료입니다.
- 이 실습자료는 ConvLab2 저장소 (https://github.com/thu-coai/ConvLab-2) 를 바탕으로 제작되었습니다.

0. 환경세팅

> (실습조교) 이 부분은 나중에 실습실 서버에 모두 설치한 후 지우도록 합시다. ConvLab-2를 `environment.yaml`로 한번에 설치할 수 없어서 아래와 같이 git submodule로 받아온 후 설치해야 합니다.

(a) ConvLab과 함께 repository를 clone
```
git clone --recurse-submodules https://github.com/tzs930/samsung_dialogue_tutorial.git
```
(b) Anaconda Environment를 생성
```
conda env create -f environment.yaml
```
(c) Anaconda Environment 활성화
```
conda activate 0813_dialogue_system 
```
(d) ConvLab-2 설치
```
pip install -e ./ConvLab-2
```

> (교육시 아래부분만 남기면 됩니다.)
```
conda activate 0813_dialogue_system
```
-----------
**실습 1.** BERT-NLU 구현 및 평가해보기 

**실습 2.** ConvLab을 활용한 Pipelined 대화시스템 실습

**실습 3.** ConvLab을 활용한 End-to-End 대화시스템 실습 

# 삼성 대화시스템 실습자료

- 이 실습자료는 8월 13일, 8월 20일에 진행될 삼성 AI-Expert 과정 실습을 위해 제작된 자료입니다.
- 이 실습자료는 ConvLab2 저장소 (https://github.com/thu-coai/ConvLab-2) 를 바탕으로 제작되었습니다.

0. 환경세팅

> (실습조교) 이 부분은 나중에 실습실 서버에 모두 설치한 후 지우도록 합시다. ConvLab-2를 `requiremets.txt`로 한번에 설치할 수 없어서 아래와 같이 git submodule로 받아온 후 설치해야 합니다.

(a) ConvLab과 함께 repository를 clone
```
git clone --recurse-submodules https://github.com/tzs930/samsung_dialogue_tutorial.git
```
(b) Anaconda Environment를 생성
```
conda env create -f requirements.txt
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
1. TRADE 모델을 활용한 대화상태 추적 (Dialogue State Tracking)
- 논문 정보 : Wu, Chien-Sheng, et al. *"Transferable Multi-Domain State Generator for Task-Oriented Dialogue Systems."* ACL 2019.
- 논문 링크 : https://arxiv.org/pdf/1905.08743.pdf
- 실습 파일 : `pratice1_TRADE.ipynb`

-----------

2. LaRL 모델을 활용한 대화정책 학습 (Dialogue Policy Learning)
- 논문 정보 :
- 논문 링크 : 

-----------
3. End-to-End 대화 에이전트 학습 : Neural Pipeline
- 논문 정보 :
- 논문 링크 : 

-----------
4. ConvLab2 Interaction
- 논문 정보 :
- 논문 링크 :
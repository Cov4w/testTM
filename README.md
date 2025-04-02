# testTM
TM 만든 JS를 테스트 해봅시다.

## Teachable Machine에서 사물인식 프로그램을 만들었습니다.
### 웹캠을 이용해 주변 사물을 TM에 업로드하여 학습시킵닏.
[!image1](images/TM_01.png)
## vsCode에서 TM 머신에서 다운받은 프로그램을 실행시킬 준비를 합니다.
### 가상환경은 파이썬 3.9버전으로 만들었습니다
'''
conda create -n prtj005_TM python=3.9
conda activate prtj005_TM
'''

## requirement.txt를 이용해 프로그램을 만들 때 설치했던 라이브러리 버전에 맞춰 설치합니다.
'''
pip install -r requirement.txt
'''
## 라이브러리 설치를 완료했다면 프로그램을 실행시킵니다.
'''
python appTM.py
'''
## 실행 화면입니다.
[!image2](images/실행결과.png)

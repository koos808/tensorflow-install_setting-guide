# Anaconda Python Tensorflow Install Guide

* 아나콘다, 파이썬 , 파이참, 텐서플로 설치 가이드
    * 기계학습개론 발표 강의 ppt 포함.
    * 자주 쓰는 conda code
        * root로 가기 ` activate root `
        * 패키지 리스트 확인 `conda list `
        * pip 업데이트 ` python -m pip install --upgrade pip `
        * 아나콘다 가상실행환경 만들기 ` conda create -n '환경이름' python=3.7 `
        * 가상환경 삭제 ` conda remove --name "환경이름" --all `
        or ` conda remove -n "환경이름" --all `
        * 가상환경으로 들어가기 ` activate tensorflow `
        * 가상환경 확인하기 `conda info "환경이름" `
        * Jupyter Notebook 멀티 커널 사용 ` pip install nb_conda `

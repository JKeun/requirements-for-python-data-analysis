# Ubuntu 에 Python 3 데이터 분석 환경 설치하기

## Virtual Machine 설치 및 Ubuntu 설치

- 동영상 : [패스트캠퍼스_컴퓨터공학 입문 SCHOOL_우분투 사전 설치](https://www.youtube.com/watch?v=Qd78TDLMxFU&feature=youtu.be)

## Ubuntu 에서 Python 3 환경 설치하기

### 1. Ubuntu 접속
- 터미널 키기 : `ctrl` + `alt` + `t` 

### 2. Python 3 & pip3 & bs4 & mysqlclient & git 설치
```
# install python3 & pip3
$ sudo apt-get install python3 python3-dev python-dev python3-pip3

# install bs4
$ sudo apt-get install python3-tk python-bs4

# install mysqlclient
$ sudo apt-get install libmysqlclient-dev 

# install git
$ sudo apt-get install git

# upgrade pip
$ sudo pip3 install --upgrade pip
```

### 3. Git clone & install requirements.txt
```
# git clone
$ git clone https://github.com/JKeun/requirements-for-python-data-analysis.git

# change directory
$ cd requirements-for-python-data-analysis

# install requirements.txt
$ sudo pip3 install -r requirements.txt

# upgrade beautifulsuop4
$ sudo pip3 install --upgrade beautifulsuop4

# remove directory
$ cd ..
$ rm -rf requirements-for-python-data-analysis
```

### 4. 확인
```
# python 실행
$ python3
```

```Python
import tensorflow
import bs4
import numpy
import pandas
import seaborn
import matplotlib
import selenium
import scipy
```

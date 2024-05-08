## 🌼 프론트엔드 5-6주차 과제 레포지토리입니다.

멋쟁이사자처럼 12기 프론트엔드 **마켓컬리** 클론 코딩

[피그마 링크](https://www.figma.com/design/QGRWFGJkl76ALiF4wJmMaS/%EB%A7%88%EC%BC%93%EC%BB%AC%EB%A6%AC-%ED%81%B4%EB%A1%A0-%EC%BD%94%EB%94%A9?node-id=0%3A1&t=ARtxG3bGHf97tu1Z-1)

---

## ✏️ 레포지토리 실행법

# 🍎 Mac

### 0. python 3.11 버전 설치

```SSH
https://www.python.org/ 에서 3.11 버전을 설치해주세요.
```

### 1. python virtualenv를 이용한 가상환경 정의

```SSH
# 프로젝트를 생성하려는 폴더경로에서 git bash를 열고..
python3.11 -m venv venv
```

---

### 2. 가상환경 실행 및 장고 설치

```SSH
source venv/bin/activate

# 최초 1회만
pip install django
```

---

### 3. 프로젝트 실행

```SSH
# manage.py 포함된 경로에서
# Model을 건들이지 않았다면, 최초 1회만 실행
python manage.py makemigrations
python manage.py migrate

python manage.py runserver
```

---

# 💻 Windows

### 1. python virtualenv를 이용한 가상환경 정의

```SSH
# 프로젝트를 생성하려는 폴더경로에서 git bash를 열고..
pip install virtualenv
virtualenv venv --python=3.11
```

---

### 2. 가상환경 실행 및 장고설치

```SSH
source venv/Scripts/activate

# 최초 1회만
pip install django
```

---

### 3. 프로젝트 실행

```SSH
# manage.py 포함된 경로에서
# Model을 건들이지 않았다면, 최초 1회만 실행
python manage.py makemigrations
python manage.py migrate

python manage.py runserver
```

---

---

## 도움을 주신분
| 이미지 | 소개 |
|:---:|:---:|
|<img src="https://github.com/LikeLion-at-DGU/12th_Front_market_kurly/assets/117021241/7d4ffaf8-aa5c-4194-b7a3-edcf3e626119" width="100" height="100" />|멋쟁이 사자처럼 12기 부회장 백엔드의 신 **이상준!**|

# 프론트엔드 5주차 과제 레포지토리입니다.

# 레포지토리 실행법

## Mac

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

## Windows

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

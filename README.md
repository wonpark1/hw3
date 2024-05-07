# 프론트엔드 5주차 과제 레포지토리입니다.

# 레포지토리 실행법

## Mac

### 1. python virtualenv를 이용한 가상환경 정의

```SSH
# 프로젝트를 생성하려는 폴더경로에서 git bash를 열고..
pip install virtualenv
virtualenv venv --python=3.12
```

---

### 2. 가상환경 실행

```SSH
# venv - bin 포함된 경로에서
source ./bin/activate
```

---

### 3. 프로젝트 실행

```SSH
# manage.py 포함된 경로에서
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

### 2. 가상환경 실행

```SSH
source venv/Scripts/activate
```

---

### 3. 프로젝트 실행

```SSH
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

---

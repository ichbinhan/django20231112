# todolist

### 建立虛擬環境
- pip install pipenv
- pipenv shell

### 安裝套件
- pip install django

### 產生專案
- django-admin startproject todolist .
- todolist為專案名稱
- .為在本地端使用產生需要的目錄與檔案

### 啟動server
- python manage.py runserver

### 同步資料庫
- python manage.py makemigrations
- python manage.py migrate

### 建立超級使用者
- python manage.py createsuperuser

### 建立網頁功能
- python manage.py startapp user

### 註冊功能
- settings
    - INSTALLED_APP
# my-JS-Django-Basic
Web Application building with Java script with Django

1. 가상환경 생성 : python venv or anaconda

2. Install Django pip : pip install Django
2-1. 장고 프로젝트 생성 : django-admin startproject <ProjectName>

3. 프로젝트 내부 Application 생성 : python manage.py startapp <ApplicationName>
3-1. 'project/settings.py'.'INSTALLED_APPS'에 Application 추가
    INSTALLED_APPS = [
        ...
        'main',
    ]


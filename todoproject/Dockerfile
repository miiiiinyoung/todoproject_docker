# 베이스 이미지 설정
FROM python:3.12.3

# 작업 디렉토리 설정
WORKDIR /app

# 필요한 패키지 설치
RUN pip install django

# 프로젝트 파일 복사
COPY . /app

# Django 서버 실행
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]

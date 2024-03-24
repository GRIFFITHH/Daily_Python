# 파이썬 베이스 이미지 사용
FROM python:3.11-slim

# 컨테이너 내의 작업 디렉토리 설정
WORKDIR /app

# 현재 디렉토리의 파일들을 컨테이너의 작업 디렉토리로 복사
COPY . .

# 필요한 패키지 설치
RUN pip install --no-cache-dir -r requirements.txt

# 애플리케이션 실행
CMD ["python", "flask_mini.py"]

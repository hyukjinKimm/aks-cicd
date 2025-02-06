# Node.js 애플리케이션을 위한 Dockerfile
FROM node:18

# 작업 디렉토리 설정
WORKDIR /usr/src/app

# 패키지 설치
COPY package*.json ./
RUN npm install

# 애플리케이션 코드 복사
COPY . .

# 애플리케이션 포트 설정
EXPOSE 8080

# 애플리케이션 실행
CMD [ "node", "app.js" ]

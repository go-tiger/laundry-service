# 기본 파일 생성
touch .gitignore
touch README.md
touch .env

# .env 세팅

PORT=3000
MYSQL_USERNAME=
MYSQL_PASSWORD=
MYSQL_DATABASE=
MYSQL_HOST=

# node modules 세팅
npm init -y

npm i dotenv ejs express mysql2 sequelize
npm i -g sequelize-cli
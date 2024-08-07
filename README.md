# Инструкция по сборке приложения

## 1. Клонирование репозитория

Клонируйте репозиторий с GitHub:

git clone https://github.com/Reivi/employeeProject.git

cd employeeProject

## 2. Настройка Backend

Сборка проекта:

cd backend

mvn clean install

Запуск Spring Boot приложения:

mvn spring-boot:run

## 3. Настройка Frontend

Перейдите в директорию frontend и установите зависимости:

cd frontend

npm install

Запуск React приложения:

npm run dev

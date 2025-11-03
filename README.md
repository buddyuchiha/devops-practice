# DevOps Lab 2: GitHub Actions CI/CD

Лабораторная работа по настройке CI/CD пайплайнов с использованием GitHub Actions для автоматической сборки и развертывания приложения

## Цель работы

Заменить самописный webhook обработчик на CI/CD пайплайны GitHub Actions и сравнить преимущества платформенного решения

## Обзор решения

### CI Pipeline (Непрерывная интеграция)
- **Триггер:** push и pull requests
- **Задачи:** установка зависимостей, запуск тестов, проверка сборки
- **Среда:** GitHub-hosted runner (Ubuntu latest)

### CD Pipeline (Непрерывное развертывание)  
- **Триггер:** создание release
- **Задачи:** сборка приложения, деплой на виртуальную машину
- **Среда:** GitHub-hosted runner + SSH доступ к VM

## ⚙️ Конфигурация

### GitHub Secrets
Для работы CD пайплайна настроены секреты:
- `SSH_HOST` - хост виртуальной машины
- `SSH_PORT` - порт SSH подключения 
- `SSH_USERNAME` - пользователь VM
- `SSH_PRIVATE_KEY` - приватный SSH ключ

[ТЗ](https://github.com/user-attachments/files/23305821/github-actions.pdf)

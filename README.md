# DevOps Labs Collection

Коллекция лабораторных работ по DevOps, демонстрирующих эволюцию процессов CI/CD и контейнеризации приложений

## Список лабораторных работ

### [Lab 1: GitHub Webhooks](https://github.com/buddyuchiha/devops-practice/tree/webhook)
**Автоматическое развертывание через GitHub Webhooks**  
Настройка автоматической сборки и деплоя Python приложения при событиях в репозитории  
**Технологии:** `GitHub Webhooks` `FRP Proxy` `Python` `FastAPI`  
**Особенности:** самописный обработчик webhook, ручное развертывание, базовая автоматизация

### [Lab 2: GitHub Actions](https://github.com/buddyuchiha/devops-practice/tree/github-actions)  
**CI/CD пайплайны на GitHub Actions**  
Замена самописного webhook обработчика на платформенное CI/CD решение  
**Технологии:** `GitHub Actions` `CI/CD` `SSH Deployment` `pytest`  
**Особенности:** автоматическое тестирование, управление секретами, визуализация workflow

### [Lab 3: Docker Containerization](https://github.com/buddyuchiha/devops-practice/tree/docker)
**Контейнеризация приложения с Docker**  
Упаковка приложения в Docker контейнеры и интеграция в CI/CD процесс  
**Технологии:** `Docker` `Containerization` `GHCR` `Dockerfile`  
**Особенности:** изоляция окружения, версионирование образов, graceful обновления

### [Lab 4: Docker Compose](https://github.com/buddyuchiha/devops-practice/tree/docker-compose)
**Управление мультиконтейнерными приложениями**  
Оркестрация нескольких сервисов с помощью Docker Compose  
**Технологии:** `Docker Compose` `MariaDB` `Multi-container` `Docker Networks`  
**Особенности:** управление зависимостями, персистентность данных, изолированные сети

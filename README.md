# Exam 06.12 (Автоматизація розгортання веб-додатку) - метод через Docker

## Опис
Цей проект містить простий Flask веб-додаток з Redis для зберігання лічильника відвідувань. Проект автоматизовано розгортається за допомогою Docker (Docker Compose) та Ansible.

## Інструкція

### Необхідні інструменти
- Git/Github
- Docker
- Ansible
- Python 3.x

Інструкція по встановлення Docker (Ubuntu) - https://docs.docker.com/engine/install/ubuntu/

Для встановлення Ansible на Ubuntu - sudo apt install ansible

ВАЖЛИВО: Перед запуском проекту, не забудьте відредагувати inventory.ini в Ansible, замінивши айпі та ім'я користувача на свої дані.

#### Запуск
Запуск містить дві прості команди:
1. Зробіть білд через Docker Compose:
   docker compose build
2. Запустіть контейнер:
docker compose up
3. Якщо запуск вдалий, перейдіть по http://localhost:5000 або http://YOUR-IP:5000



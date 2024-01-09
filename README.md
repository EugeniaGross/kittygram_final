### Описание проекта
Kittygram - сайт с возможностью публикации фотографий, имени, года рождения и достижений котов, просмотра, редактирования, удаления.

### Клонирование проекта
```
git clone https://github.com/EugeniaGross/kittygram_final.git
```

### Запуск проекта из Docker image
Cоздаём папку проекта и переходим в нее:

```
mkdir <название_папки>
```

```
cd <название_папки>
```

В папку проекта копируем из kittygram_final docker-compose.production.yml, создаем .env (c образцом можно ознакомиться kittygram_final/.env/example) и запускаем:

```
sudo docker compose -f docker-compose.production.yml up
```

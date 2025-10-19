# learn-fullstack-with-sluvik
## Инструкция запуска frontend проекта на Nuxt
1. Установите зависимости:
```bash
npm install
``` 
2. Запустите проект в режиме разработки:
```bash
npm run dev
```
3. Откройте браузер и перейдите по адресу:
```
http://localhost:3000
```

## Инструкция запуска backend проекта на FastAPI
1. Создайте и активируйте виртуальное окружение:
```bash
python -m venv venv

```

Для Windows:
```bash
venv\Scripts\activate  # Для Windows
```
Для macOS/Linux:
```bash
source venv/bin/activate  # Для macOS/Linux
```

2. Установите зависимости:
```bash
pip install -r requirements.txt
```
3. Запустите сервер FastAPI:
```bash
fastapi dev main.py
```

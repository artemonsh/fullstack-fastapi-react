# Крипто трекер / Crypto Tracker
![app.png](docs/app.png)
#### Ссылка на видео урок по этому проекту: https://youtu.be/C9C2EqtVJbQ

## Стек
- FastAPI + pydantic, pydantic-settings, aiohttp
- React + axios, ant design, tailwind


### Инструкции
#### Backend
- `python3 -m venv venv`
- `. venv/bin/activate` или `.\venv\Scripts\activate.bat`
- `pip install -r requirements.txt`
- `uvicorn src.main:app --reload` (обязательно находясь внутри папки backend)

#### Frontend
- `npm create vite@latest`
- `npm install`
- `npm run dev`
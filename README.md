# ReelTrack

## Технології

- **Фронтенд:** React (Vite + JavaScript + SWC + Tailwind CSS)
- **Бекенд:** Node.js (Express)
- **База даних:** MongoDB Atlas

## Опис

**ReelTrack** — це учнівський проєкт, розроблений у рамках навчання в університеті.  
Мета проєкту — створити сучасну платформу для відстеження відеоконтенту, зручну для користувачів.

## Розробники

- [Босенко Христина](https://github.com/kartuj4)
- [Дригалка Данило](https://github.com/Yttterbium)
- [Коваленко Сергій](https://github.com/Serhii0659)
- [Ткаченко Дмитро](https://github.com/uddorn)

## Встановлення

1. Клонуйте репозиторій:
    ```bash
    git clone --recurse-submodules https://github.com/Serhii0659/ReelTrack
    ```
2. Створіть свої `.env` файли у папках `client` та `server` (див. приклади нижче).
3. Перейдіть у директорію клієнта:
    ```bash
    cd ReelTrack/client
    ```
4. Встановіть залежності:
    ```bash
    npm install
    ```
5. Запустіть фронтенд у режимі розробки:
    ```bash
    npm run dev
    ```
6. В іншому терміналі перейдіть у директорію серверу:
    ```bash
    cd ../server
    npm install
    ```
7. Запустіть сервер у режимі розробки:
    ```bash
    npm run dev
    ```

## Приклад .env для server

```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
TMDB_API_KEY=your_tmdb_api_key
CLIENT_URL=http://localhost:5173
CLIENT_URL_PROD=https://your-production-frontend-url
NODE_ENV=development
```

## Приклад .env для client

```
VITE_API_BASE_URL=http://localhost:5000
VITE_TMDB_API_KEY=your_tmdb_api_key
```

## API

Документація API знаходиться у server/README.md.

## Ліцензія

Цей проєкт ліцензовано під умовами GNU General Public License v3.0.  
Детальніше читай у файлі LICENSE.
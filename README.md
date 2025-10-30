# ChatBot_Instruction
К
```markdown
# Инструкция по запуску проекта AML/CFT Chatbot

---

## 📍 Путь к проекту
```

Диск D:\Kaminur

```

---

## 💻 **Frontend (React + Vite)**

### 1️⃣ Открытие командной строки
Нажмите **Win + R**, введите:
```

cmd

````
и нажмите **Enter**.

---

### 2️⃣ Перейдите на диск D:
```bash
D:
````

### 3️⃣ Перейдите в директорию проекта:

```bash
cd D:\Kaminur\Chatbot_FrontEnd-main\Chatbot_FrontEnd-main
```

### 4️⃣ Запустите фронтенд-сервер:

```bash
npm run dev
```

После успешного запуска вы должны увидеть что-то вроде:

```
VITE v7.1.11  ready in 409 ms
→ Local:  http://localhost:5173/
```

📍 **Frontend** теперь доступен по адресу:
👉 [http://localhost:5173/](http://localhost:5173/)

---

## ⚙️ **Backend (FastAPI)**

### 1️⃣ Активируйте виртуальное окружение:

```bash
venv\Scripts\Activate.ps1
```

> 💡 Если PowerShell блокирует выполнение скриптов, выполните команду:
>
> ```bash
> Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
> ```

---

### 2️⃣ Запустите сервер FastAPI:

```bash
uvicorn app.main:app --reload --host 127.0.0.1 --port 8000
```

После запуска backend будет доступен по адресу:
👉 [http://127.0.0.1:8000](http://127.0.0.1:8000)

Документация Swagger:
👉 [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

## ✅ Проверка подключения

1. Убедитесь, что **backend** запущен (`uvicorn` работает без ошибок).
2. Затем запустите **frontend** (`npm run dev`).
3. Перейдите на [http://localhost:5173](http://localhost:5173)
   — вы должны увидеть интерфейс чат-бота.

Если отображается сообщение
`⚠️ Не удалось подключиться к серверу`,
проверьте:

* правильность URL в `.env`:

  ```
  VITE_API_URL=http://127.0.0.1:8000
  ```
* что backend запущен именно на этом адресе и порту.

---

## 🧩 Полезные ссылки

* 🌐 Frontend: [http://localhost:5173](http://localhost:5173)
* ⚙️ Backend API: [http://127.0.0.1:8000](http://127.0.0.1:8000)
* 📘 Swagger-документация: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

✨ **Теперь всё готово для запуска чат-бота AML/CFT!**

```

---

Хочешь, чтобы я добавил туда снизу секцию  
**🧠 Возможные ошибки и решения (npm / venv / CORS / порт занят)** — для продакшн-уровня README?
```

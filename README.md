Вот более **чистая и лаконичная** версия README, идеально подходящая для вставки в GitHub:

---

````markdown
# 🧠 ChatBot_Instruction

## 📍 Путь к проекту
**Диск:** `D:\Kaminur`

---

## 💻 Front-End (React + Vite)

1️⃣ Откройте **Command Prompt** с помощью **Windows + R**, введите:
```bash
cmd
````

2️⃣ Перейдите на диск **D:**

```bash
D:
```

3️⃣ Перейдите в директорию проекта:

```bash
cd D:\Kaminur\Chatbot_FrontEnd-main\Chatbot_FrontEnd-main
```

4️⃣ Запустите фронтенд:

```bash
npm run dev
```

После запуска вы должны увидеть что-то вроде:

```
VITE v7.1.11 ready in 409 ms
→ Local: http://localhost:5173/
```

👉 **Frontend:** [http://localhost:5173/](http://localhost:5173/)

---

## ⚙️ Back-End (FastAPI)

1️⃣ Активируйте виртуальное окружение:

```bash
venv\Scripts\Activate.ps1
```

2️⃣ Запустите сервер:

```bash
uvicorn app.main:app --reload --host 127.0.0.1 --port 8000
```

👉 **Backend:** [http://127.0.0.1:8000](http://127.0.0.1:8000)
📘 **Swagger Docs:** [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

✅ **Теперь всё готово!**
Фронтенд работает на `5173`, а бэкенд — на `8000`.

```

---

Хочешь, чтобы я сделал короткую английскую версию в том же формате (на случай, если README будет для внешних коллег)?
```

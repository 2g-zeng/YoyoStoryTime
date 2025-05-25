
# 📦 Yoyo Story Time – Backend

This is the **FastAPI backend**. It provides API endpoints for handling user profiles, generating personalized stories and much more.

---

## 🚀 Features

- 🔐 User authentication
- 📝 Story generation
- 💾 File upload to S3
- 🗃 Metadata storage in DynamoDB

---


## 🛠 Getting Started (Local)

```bash
cd backend
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
uvicorn app.main:app --reload
```

The server will run on `http://localhost:8000`.

---


## 📬 Key Endpoints

| Method | Endpoint        | Description             |
|--------|-----------------|-------------------------|
| POST   | `/generate`     | Generate a new story    |
| GET    | `/stories`      | Get saved stories       |
| POST   | `/profile`      | Upload user info        |

---


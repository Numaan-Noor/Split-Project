

## Features ⭐

⚡️ Add users/members to the application (CURD)\
⚡️ Create groups and add new members to the group (CRUD)\
⚡️ Add expenses in the group and let the application handle all the spliting

## Folder Structure :file_folder:

```
.
├── Procfile
├── README.md
├── app.py
├── application
│   ├── __init__.py
│   ├── config
│   │   └── __init__.py
│   ├── controllers
│   │   ├── expense.py
│   │   ├── group.py
│   │   ├── simplify.py
│   │   ├── transaction.py
│   │   └── user.py
│   └── models
│       ├── expense.py
│       ├── group.py
│       ├── transaction.py
│       ├── user.py
│       └── user_group.py
├── practice.py
├── requirements.txt
├── runtime.txt
└── wsgi.py
```

Entry point is `app.py`. All the models are being stored in `models`. All the routes are structured in `controllers`.

## Install & Build 🛠️

**Step 1:** Install all the dependencies.

```
pip install -r requirements.txt
```

**Step 2:** Run the server. (Make sure `.env` is already has all the required environment variables)

```
python app.py
```


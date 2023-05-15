# chat-api steps:

```sh
1- python -m venv venv
2- python -m pip install --upgrade pip setuptools
3- pip install --upgrade -r requirements.txt
4- pip install -r requirements.txt
5- uvicorn app.api:main --reload
------------------------------------------
Uvicorn running on http://127.0.0.1:8000
------------------------------------------
```

## Should create a .env file to add the values of:

| Values | You can find it here. |
| ------ | ------ |
| SUPABASE_URL | supabase.com |
| SUPABASE_SECRET_KEY | superbase.com - Tokens |
| AUTH0_DOMAIN | auth0.com - Settings |
| AUTH0_CLIENT_ID | auth0.com - Applications |
| AUTH0_CLIENT_SECRET | auth0.com - Settings |
| API_AUDIENCE | auth0.com - Applications - API |

![N|Solid](https://i.ibb.co/qrpY3DR/Screenshot-from-2023-05-15-18-11-20.png)



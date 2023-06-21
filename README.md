# Django4.2_Passkeys_Login_Demo

## How to use

```
pip3 install -r requirements.txt
```

```
python3 manage.py migrate
```

```
python manage.py createsuperuser
```

```
python manage.py runsslserver --cert ./server.crt --key ./server.key  0.0.0.0:8000
```

Visit  https://localhost:8000
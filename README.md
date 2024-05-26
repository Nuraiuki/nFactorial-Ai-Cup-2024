# How to run 

* go to server folder

```
cd server
```

* create venv

```
python3 -m venv venv
```

* activate venv
```
source venv/bin/activate
```

* install requirements

```
pip3 install -r requirements.txt
```

* setup database

```
python3 manage.py migrate
```

* run server

```
python3 manage.py runserver
```

# How to use and test

* install Postman and set this URL to test

```
http://localhost:8000/api/generate-recipes/
```

* set body 

```
{
    "items": [
        "macaroni, butter, salt, bacon, milk, flour, pepper, cream corn"
    ]
}

```

* run

<img width="1440" alt="image" src="https://github.com/SultokTheF/Ratatui/assets/70005427/31b9a069-bfed-4885-bc07-38ceb2fb15b4">



* create new terminal

```
cd client
```

* run emulator

```
flutter emulators --launch ios
```

* run it

```
flutter run
```












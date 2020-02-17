# Weather Api Test Task
Weather API Test

### Install Mysql Database
```
- sudo apt install mysql-server
- Create Database 'weatherApi' in Mysql Database
```

### Install Requirements
```
- sudo pip install -r requirements.txt
```

### Weather Service example
```
- https://samples.openweathermap.org/data/2.5/weather?q=London,uk&appid=b6907d289e10d714a6e88b30761fae22
- APP_ID = 'b6907d289e10d714a6e88b30761fae22'
```
### Database settings 

```
- in the file WeatherApi/settings.py add mysql variables to connect to the database

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'weatherApi',
        'USER': 'root',
        'PASSWORD': 'root',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

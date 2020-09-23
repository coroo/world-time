### Fast Api - World Time

Dependencies Installation
```
pip3 install fastapi
pip3 install requests
```
Dependencies Server Run
```
pip3 install hypercorn
```

------

### Run App
```
hypercorn main:app --reload
```
### Run Swagger

Go to [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs) or another documentation at [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

------

### World API
Created using [worldtimeapi](http://worldtimeapi.org). Here sample usage for insert body request.
```
{
  "name": "Las Vegas",
  "timezone": "America/Los_Angeles"
}
```
For more timezone value related: http://worldtimeapi.org/api/timezone/

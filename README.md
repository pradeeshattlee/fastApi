### initialization
In command terminal run the following command
```shell
py -m venv env
env/Scripts/activate
python -m pip install -U pip
pip install -r requirements.txt
```

## Run the app 
In command terminal run the following command
```shell
uvicorn main:app --reload
```
open http://localhost:8000/notes/ in web browser to check if application runs

## make the app calls on postman
import the file in postman  ## Fastapi.postman_collection.json


## Available api methods
```shell
Fastapi
Make things easier for your teammates with a complete collection description.
POST
http://localhost:8000/notes/
http://localhost:8000/notes/
Add

Request Headers
Content-Type
application/json
Bodyraw (json)
json
{
  "text": "Get Groceries from the store",
  "completed": false
}
GET
http://localhost:8000/notes/
http://localhost:8000/notes/
retrieve

PUT
http://localhost:8000/notes/1
http://localhost:8000/notes/1
update

Request Headers
Content-Type
application/javascript
Bodyraw (javascript)
javascript
{
  "text": "Get Groceries from the store updated",
  "completed": false
}
GET
http://localhost:8000/notes/1
http://localhost:8000/notes/1
get particular entry

DEL
http://localhost:8000/notes/1
http://localhost:8000/notes/1
delete entry
```

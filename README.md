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


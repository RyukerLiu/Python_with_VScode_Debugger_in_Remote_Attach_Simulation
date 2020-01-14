# Remote Debug


## With ptvsd in code

Start script with ptvsd first


``` bash
cd ./remote_test

pipenv install

pipenv shell

python greeting.py
```

Then Start VScode Debugger with Python: Remote Attach
And Set breakpoint

## Use python -m (Without ptvsd in code)

``` bash
cd ./remote_test

pipenv install

pipenv shell

python -m ptvsd --host localhost --port 3000 --wait -m greetings_use_-m
```

Then Start VScode Debugger with Python: Remote Attach
And Set breakpoint


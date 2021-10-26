# HandsOn Python


## Extensions VSCode

### Code Runner

https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner

### Python

https://marketplace.visualstudio.com/items?itemName=ms-python.python


## Theme Dracula Official

https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula


## VSCode Icons

https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons

## Commands

### Create Project

```shell
mkdir hands-on-python
cd hands-on-python
code .
```

### Create Enviroment Virtal

```shell
python3 -m venv .venv
```

### Activate Enviroment Virtal

```shell
. .venv/bin/activate
```


```
pip install --upgrade pip
pip install mypy
pip install flake8
```


### Deactivate Enviroment Virtual

```shell
deactivate
```
### VSCode Settings (Project)

```json
{
    "python.pythonPath": ".venv/bin/python",
    "code-runner.executorMap": {
        "python": ".venv/bin/python",
    },
    "code-runner.ignoreSelection": true,
    "code-runner.runInTerminal": true,
    "python.linting.mypyEnabled": true,
    "python.linting.flake8Enabled": true,
    "python.testing.unittestEnabled": true,
    "[python]": {
        "editor.formatOnSave": true
    }
}
```

## Extra Commands

```shell
python -m unittest discover 
python -m unittest discover -v
```

## References

[YOUTUBE - Configurando o VS Code para Python](https://www.youtube.com/watch?v=ZQ60SJDACuc)
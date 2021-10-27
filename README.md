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
pip install autopep8
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

[Youtube - Configurando o VS Code para Python](https://www.youtube.com/watch?v=ZQ60SJDACuc)

[Diferença entre MyPy e Flake8](https://cursos.alura.com.br/forum/topico-diferenca-entre-mypy-e-flake8-116368)

[Project: mypy](https://pypi.org/project/mypy/)

[Project:  flake8](https://pypi.org/project/flake8/)

[Project: autopep8](https://pypi.org/project/autopep8/)

[black VS autopep8](https://www.libhunt.com/compare-black-vs-autopep8)
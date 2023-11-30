# 2023 Advent of Code

## Installation

Installed Poetry [Introduction | Documentation | Poetry - Python dependency management and packaging made easy](https://python-poetry.org/docs/#installing-with-the-official-installer)

```Powershell
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
```

Poetry not on the path solved by ["python - Poetry installed but `poetry: command not found` - Stack Overflow"](https://stackoverflow.com/questions/70003829/poetry-installed-but-poetry-command-not-found/75601518#75601518)

```Powershell
$Env:Path += ";C:\Users\YourUserName\AppData\Roaming\Python\Scripts"; setx PATH "$Env:Path"

Make the virtual env in the project so that VSCode can see it.

```Powershell
poetry config virtualenvs.in-project true
poetry install
```

Get some dependencies out of the way

```Powershell
poetry add numpy pandas jupyter ipykernel
```

Get a new jupyter notebook going - https://www.youtube.com/watch?v=h1sAzPojKMg

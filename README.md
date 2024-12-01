# 2023 Advent of Code

## Run

`uv run jupyter notebook`

## Installation

pip install uv

```Powershell
$Env:Path += ";C:\Users\YourUserName\AppData\Roaming\Python\Scripts"; setx PATH "$Env:Path"
```

```Bash
PATH=/c/Users/YourUserName/AppData/Local/Programs/Python/Python313:/c/Users/YourUserName/AppData/Local/Programs/Python/Python313/Scripts:$PATH
```

Get a new jupyter notebook going - https://www.youtube.com/watch?v=h1sAzPojKMg

## Set up

In the past, I kept the data in text files next to the notebooks so that they weren't in the way. I found out that there is a MUCH better option advent-of-code-data package.

You'll need to export the session token to `~/.config/aocd/token`. More help on [the package website](https://pypi.org/project/advent-of-code-data/) if needed.

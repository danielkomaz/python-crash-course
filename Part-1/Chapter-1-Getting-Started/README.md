# Chapter 1 - Getting Started

In this chapter we will set up a development environment and write the first script.

## Install Software

I will install my environment different from how it is described the book, as I already know and use other tools which I am very comfortable with.

| Software           | Provider   | Installation Command   |
| ------------------ | ---------- | ---------------------- |
| Visual Studio Code | Chocolatey | `choco install vscode` |
| Python3            | Chocolatey | `choco install python` |

## Writing The First Script

Create a new file called `hello_world.py` with the following content:

```Python
print("Hello Python world!")
```

## Run Script

To run the script we only need to execute the following command in the same directory as our script:

```Powershell
python .\hello_world.py
```

## Run Commands In Python Shell

To open the python terminal/shell you only need to run:

```Powershell
python
```

After that you can run any python command you want directly in the shell like this:

```Python
print("Hello Python world!")
```

This would give the same result as if you would have run the script.

## Exit Python Shell

To exit the shell again use the function `exit()` or press `Ctrl-Z plus Return`.

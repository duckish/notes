
## Welcome to Pyenv notes

1. [kind](./kind.md)
2. [kubectl](./kubectl.md)
3. [pyenv](./pyenv.md)
4. [helm](./helm.md)

### Version

List all avalaible versions

```markdown
pyenv install --list
```
Install python version

```
pyenv install -v X.X.X
```
List all installed version

```
pyenv versions
```
Switch to version that we want to use

```
pyenv global X.X.X
```

Creating a virtual environment is a single command
```
pyenv virtualenv <python_version> <environment_name>
```

Active virtual env
```
pyenv local myproject
```

## What is pip for?

You can install, upgrade, and remove packages using a program called  **pip** .

[https://docs.python.org/3/tutorial/venv.html](https://docs.python.org/3/tutorial/venv.html)

Install package

```
(envname) $ python -m pip install novas
# Install package with specific version
(envname) $ python -m pip install requests==2.6.0
```

Upgrade

```
(tutorial-env) $ python -m pip install --upgrade requests
```

Remove

```
(tutorial-env) $ python -m pip install --upgrade requests
```

display information

```
(tutorial-env) $ python -m pip show requests
```

display all of the packages

```
(tutorial-env) $ python -m pip list
```

Output all of the packages

```
(tutorial-env) $ python -m pip freeze > requirements.txt
(tutorial-env) $ cat requirements.txt
```

install all the necessary packages

```
(tutorial-env) $ python -m pip install -r requirements.txt
```

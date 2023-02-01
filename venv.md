# What is venv?

Venv is a module used to create and manage virtual environments. venv will usually install the most recent version of Python that you have available. If you have multiple versions of Python on your system, you can select a specific Python version by running python3 or whichever version you want.

Useful link: [https://docs.python.org/3/tutorial/venv.html](https://docs.python.org/3/tutorial/venv.html)

On Ubuntu prompt, run:

### Create a venv with name `venvname`

```bash
python3 -m venv venvname
# Create virtual environment with a specific version
python3.7 -m venv venvname
python3.9 -m venv venvname
```

### Activate the virtual environment

```bash
source venvname/bin/activate
```

### Deactivate the virtual environment

```bash
deactivate
```

# Gradient Remover

To install, clone this repository and enter it.
We require poetry to install it.
Then run

```
# If you want to use a poetry virtualenv, first activate the shell
poetry shell
# This is required regardless 
poetry install
```

It is recommended to then exit the shell (with `exit`).
You can verify that it is set up correctly by running

```
poetry run pytest
```

which should run the test suite in the correct shell and pass.
To enter the shell that this is installed in, simply enter the directory
and run 

```
poetry shell
```

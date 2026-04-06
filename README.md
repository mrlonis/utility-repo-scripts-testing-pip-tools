# utility-repo-scripts-testing

## Compiling Requirements

```shell
pip-compile requirements.in
```

## Updating Requirements

```shell
pip-compile --upgrade requirements.in
```

## Syncing Requirements

```shell
pip-sync requirements.txt
```

## Linting

```shell
flake8 src tests
pylint src tests
```

## Testing

```shell
pytest --cov=src tests/ -n auto
```

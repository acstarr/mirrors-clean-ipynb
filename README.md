clean_ipynb mirror
===========

Mirror of clean_ipynb for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For clean_ipynb: see https://github.com/KwatME/clean_ipynb

### Using clean_ipynb with pre-commit:

Add this to your `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/acstarr/mirrors-clean-ipynb
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: clean_ipynb
```


By default, clean_ipynb will run with `clean_ipynb --overwrite`.
To change the arguments, override the `args` as follows:

```yaml
    hooks:
    -   id: clean_ipynb
        args: []
```

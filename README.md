
### Service dep
___

Provides a development environment and configuration tools for easily creating new web services.

#### Features

* Service settings collected in pyproject.toml
* Overload service settings from os env
* Service spec with runtime
* Json logs
* Static i18n translates
* i18n middleware, etc
* Sentry support
* Testing tools


### Install
```shell script
pip install service-dep
```

### Testing
Run tests with:

```shell script
poetry run pytest
```

or with verbose output:
```shell script
poetry run pytest -vv -s
```

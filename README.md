# Stepik Django Rest Framework tests
[![Build Status](https://travis-ci.com/stepik-a-w/drf_tests_app.svg?branch=master)](https://travis-ci.com/stepik-a-w/drf_tests_app)
[![codecov](https://codecov.io/gh/stepik-a-w/drf_tests_app/branch/master/graph/badge.svg?token=TJZPZGR1B8)](https://codecov.io/gh/stepik-a-w/drf_tests_app)

This Django application shows API testing best practices collected from Stepik's Django Rest Framework [course](https://stepik.org/course/73594/).

# Highlights
* [Coverage settings](https://github.com/stepik-a-w/drf_tests_app/blob/master/.coveragerc)
* [BookViewSet tests](https://github.com/stepik-a-w/drf_tests_app/blob/master/src/apps/books/tests/test_bookviewset.py)

# Installation
```sh
$ pip install pipenv
$ pipenv install -dev
```

# Configuration
Pass `POSTGRES_DB`, `POSTGRES_USER`, `POSTGRES_PASSWORD`, `POSTGRES_HOST` and `POSTGRES_PORT` environments to Django
**or** copy `settings/base/db.py` to `settings/local/db.py` and feel free to change local settings. Yes, it works for all 
settings from `base`.

# Running tests
```sh
$ python manage.py test
```
# Checking coverage
```sh
$ coverage run
```

## License
MIT

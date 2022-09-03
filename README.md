### Hexlet tests and linter status

[![Actions Status](https://github.com/tommyqamaz/python-project-51/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/tommyqamaz/python-project-51/blob/main/.github/workflows/hexlet-check.yml)
[![Project-check](https://github.com/tommyqamaz/python-project-51/actions/workflows/python-ci.yml/badge.svg)](https://github.com/tommyqamaz/python-project-51/blob/main/.github/workflows/python-ci.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/b37a718090ca39bc83de/maintainability)](https://codeclimate.com/github/tommyqamaz/python-project-51/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/b37a718090ca39bc83de/test_coverage)](https://codeclimate.com/github/tommyqamaz/python-project-51/test_coverage)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
## Installation
### Install
<code>git clone git@github.com:tommyqamaz/page-loader.git</code>

<code>pip install poetry</code>

<code>make assembly</code>
## Usage

### As external library

```python
from page_loader import download

file_path = download('https://ru.hexlet.io/courses', '/var/tmp')
print(file_path)  # => '/var/tmp/ru-hexlet-io-courses.html'
```

### As CLI tool

```
# по умолчанию output это os.getcwd()
page-loader --output /var/tmp https://ru.hexlet.io/courses
/var/tmp/ru-hexlet-io-courses.html  # путь к загруженному файлу
```

## About page-loader
This is a cli utility that allows you to download web pages with all the contents.

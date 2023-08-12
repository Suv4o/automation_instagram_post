# Automation of uploading and posting Instagram posts using Python and `pyppeteer`

## Prerequisites

This project uses `pipenv` to handle all dependencies. For more information on how to use `pipenv`, please refer to the following documentation: https://pipenv.pypa.io/en/latest/

However, if you prefer not to use `pipenv`, a `requirements.txt` file has been created and can be used with `pip` as well.

## Before you start

Make sure to create a `.env` file in the root of the project and add the following variables:

```
INSTAGRAM_USER_NAME='your_instagram_user_name'
INSTAGRAM_PASSWORD='your_instagram_password'
```

## Installation

```bash
$ pipenv install
```

## Start the project

```bash
$ pipenv run python app.py
```

## VS Code setup

Add the following to your `settings.json`:

```json
{
    "[python]": {
        "editor.defaultFormatter": "ms-python.black-formatter",
        "editor.formatOnSave": true
    },
    "python.formatting.blackArgs": ["--line-length", "120"],
    "files.associations": {
        "*.py": "python"
    },
    "python.analysis.importFormat": "relative"
}
```

# androgee
[![Build Status](https://travis-ci.com/Egeeio/androgee.svg?branch=main)](https://travis-ci.com/Egeeio/androgee)

Requirements & venv are handled by Poetry - https://python-poetry.org/docs & https://python-poetry.org/docs/basic-usage.
You will need to use [type hints](https://www.python.org/dev/peps/pep-0484/) in your code for mypy's pre-commit hook. Before you commit use `poetry shell` so you have a environment with[`pre-commit`](https://pre-commit.com) installed.

To run:
* set the following environment variables:
    - `DISCORD_PREFIX`
    - `DISCORD_TOKEN`
    - `MOD_ROLE_ID`
    - `MOD_ROLE_NAME`
    - `MOTD_CHANNEL`
* do `poetry install`
* and then `poetry run start`

![Androgee!!](.github/Androgee_-_Reference_Sheet.jpg)

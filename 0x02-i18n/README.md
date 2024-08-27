# 0x02. i18n

This project focuses on implementing internationalization (i18n) in a Flask application. It covers various aspects of i18n, including setting up Flask-Babel, parametrizing templates, inferring correct locales, and localizing timestamps.

## Learning Objectives

- Parametrize Flask templates to display different languages
- Infer the correct locale based on URL parameters, user settings or request headers
- Localize timestamps

## Requirements

- All files interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
- All files should end with a new line
- First line of all files should be exactly `#!/usr/bin/env python3`
- Code should use the pycodestyle style (version 2.5)
- All modules, classes, and functions should have documentation
- All functions and coroutines must be type-annotated

## Files

- `0-app.py`: Basic Flask app
- `1-app.py`: Basic Babel setup
- `2-app.py`: Get locale from request
- `3-app.py`: Parametrize templates
- `4-app.py`: Force locale with URL parameter
- `5-app.py`: Mock logging in
- `6-app.py`: Use user locale
- `7-app.py`: Infer appropriate time zone
- `app.py`: Display the current time (advanced)
- `babel.cfg`: Babel configuration file
- `templates/`: Directory containing HTML templates
- `translations/`: Directory containing translation files

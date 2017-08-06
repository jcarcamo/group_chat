# Juan Gonzalo Carcamo Implementation

This implementation was inspired by the post from Jonathan Cox [Using React with Django, with a little help from Webpack](http://geezhawk.github.io/using-react-with-django-rest-framework). Django 1.8.4 was used in this tutorial and so it was the version used for this implementation.

# Installation

Clone this repository and run:
```bash
npm init
npm install --save-dev jquery react react-dom webpack webpack-bundle-tracker \
    babel-loader babel-core babel-preset-es2015 babel-preset-react
./node_modules/.bin/webpack --config webpack.config.js
pip install -r requirements.txt
python manage.py migrate
# To run it:
python manage.py runserver
```

## Tech used

### Frontend
* Webpack
* React
* HTML/CSS bootstrap

### Backend:
* Python Django 1.8.4
* Django Rest Framework
* Webpack loader

### Platform:
* TBD

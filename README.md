# HTML Form processor

A flask app that prints submitted form-data. Helpful for beginners to understand how HTML forms submit data to backend.

## Requirements

1. Python >= 3.8
2. VirtualEnvWrapper

See this [blogpost](https://www.webinative.com/blog/setting-up-python-virtual-environments/) to setup virtualenvwrapper.

## How to run this app

Follow the instructions below,

```sh
cd ~/Dev
git clone git@github.com:Webinative/html-form-processor.git
cd html-form-processor

# create a new virtual environment
mkvirtualenv flask_app

pip3 install Flask

# TODO: Edit templates/form.html to place your form.

# run the flask app
flask --app flask_app --debug run
```

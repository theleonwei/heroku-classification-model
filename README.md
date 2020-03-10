# This repo is for the following medium article:
https://medium.com/@data.leon/django-for-data-scientists-deploy-a-machine-learning-model-with-django-and-heroku-a6919eb3f757

# Deploy your model to Heroku

## Download this repository, then

    $ git init
    $ git add -A
    $ git commit -m "Initial commit"

    $ heroku create
    $ git push heroku master

### Now you should be able to visit the api
https://YOUR-HEROKU-APPNAME.herokuapp.com/model/api/predict/?review=beautiful%20movie

### You can visit my app:
#### https://morning-plains-31313.herokuapp.com/model/api/predict/?review=beautiful%20movie

### You can also use tool such as cURL to make a get request directly:
    $ curl 'http://morning-plains-31313.herokuapp.com/model/api/predict/?review=This%20movie%20sucks'


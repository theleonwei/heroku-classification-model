# This repo is for this blog published on data scientist school.
https://datascientistschool.com/blog/209984/deploy-a-machine-learning-model-to-heroku-with-django

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

